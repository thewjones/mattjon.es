---
type: post
comments: true
date: 2012-12-14T10:56:46Z

title: Fixing a non-booting Raspberry Pi (constant green LED, no video)

wordpress_id: 5044
---

If you're a new Raspberry Pi owner, here's a tip for saving you hours of frustration getting the thing to boot up. If your Pi doesn't boot, it may be an issue with your SD card but it's more likely to be the way you've written the image to the drive.

After inserting the SD card, the last few lines of the output of the 'dmesg' command will tell you the identity of the SD card. In my case - running Ubuntu - this was 'mmcblk0', so the path to write the image to is '/dev/mmcblk0'

dd bs=1M if=/home/matt/Downloads/debian6-19-04-2012/debian6-19-04-2012.img of=/dev/mmcblk0
