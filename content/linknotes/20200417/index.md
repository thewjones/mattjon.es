---
date: 2020-04-20T15:32:00Z
tags:
- Community
- Health
- Neighbourliness
resources:
- name: header
  src: teletype-machine.jpg
title: Link Notes 20 Apr 2020
imageCaption: Image from page 646 of "The Bell System technical journal" (1922)
imageAttrib: Prelinger Library
imageURL: https://www.flickr.com/photos/internetarchivebookimages/14753014981/in/photolist-otF4ng-qsD9N3-x1cV5J-t4gwJa-soKVxE-t4iZtt-t4whsL-otHsP2-otVhD9-wKTAky-otJRqq-t49ZYJ-tiqg6w-xd74x7-ou6Gzq-t4hYZ4-otQb4q-rppea4-soVrFB-ou15u2-ouqKgt-t4bD4q-f9Z1kB-x2KCpW-wL1PKz-orPUjq-x44kpR-soJKNG-fbs3Jm-f8Di2D-x1cx7A-x1cqyL-tir5So-w6udGG-x1cNpu-wKT2bq-w6uYsN-x43bp8-t49P4Y-x2KPEb-w6tdgo-x1c7RG-xuad3t-x44FnM-w6toPC-x3vW5k-soWq1F-x41VKk-oy5LV8-odnTLx
licenseURL: https://creativecommons.org/share-your-work/public-domain/cc0/
imageLicense: CC0
---

## Today's links

* [Using a 1930 Teletype as a Linux Terminal](/blog/links/2020/04/20#using-a-1930-teletype-as-a-linux-terminal): Using 1930s tech to operate a modern computer.
* [Pluralistic](/blog/links/2020/04/20#pluralistic-daily-links-from-cory-doctorow): Cory Doctorow's daily links and inspiration for this site.
* [The night sky is increasingly dystopian](/blog/links/2020/04/20#the-night-sky-is-increasingly-distopian): How SpaceX and other companies may be messing up the night sky for everyone.
* [Hugo](/blog/links/2020/04/20#hugo): The static site generator I'm using to manage this site.

<!--more-->

---

### Using a 1930 Teletype as a Linux Terminal

This video of [Marc Verdiell](https://www.curiousmarc.com/about) using some serious electronic engineering skills to set up a 1930s Teletype machine as a Linux terminal will be nerdiest thing you'll see today.

https://www.youtube.com/watch?v=2XLZ4Z8LpEE

[Teletype machines](https://en.wikipedia.org/wiki/Teleprinter) like this are in the DNA of every computer and phone we use (except perhaps ones running Microsoft software). The filesystem on your Mac (or even your iPhone) has files at /dev/tty* - these are the input/output devices available to the operating system, which could be any kind of peripheral device you have connected.

'TTY' is an abbreviation of TeleTYpe, after the original Teletype machines that were used by computer operators in the 60s and 70s to enter commands and retrieve output.

In the video we see Marc use a single-line editor called '[ed](https://en.wikipedia.org/wiki/Ed_(text_editor)' which is software originally built into UNIX in the 1960s. If you use a Mac, or any [POSIX](https://en.wikipedia.org/wiki/POSIX) compliant computer, you can open your Terminal utility and type 'Ed' to still use this software.

{{< imgproc name="teletype"
    command="Resize"
    options="1200x"
    imageCaption="Switch lists coming in by teletype to the hump office at a Chicago and Northwestern railroad yard, Chicago, Illinois. c. 1939" imageURL="https://picryl.com/media/switch-lists-coming-in-by-teletype-to-the-hump-office-at-a-chicago-and-northwestern"
    imageAttrib="US Library of Congress"
    imageLicense="CCO"
    imageURL="https://picryl.com/media/switch-lists-coming-in-by-teletype-to-the-hump-office-at-a-chicago-and-northwestern"
    licenseURL="https://creativecommons.org/share-your-work/public-domain/cc0/">}}


---

### Pluralistic: Daily links from Cory Doctorow

https://pluralistic.net

Part of the problem with my motivation to write this blog is that the direction I took some years back was to publish only long-form pieces of writing, as opposed to linking across to web pages that interested me.

An article based format isn't particularly conducive to quick publishing of links and thoughts and in turn a regularly updated blog that people want to engage with.

This most recent interation of my blog has been in place for a couple of years now and while I'm happy with the design, speed and simplicity of the site,  I've found it difficult find the motivation and time to write for it.

I recently visited Cory Doctorow's [Pluralistic](https://pluralistic.net) and really liked the format of link + comment, and the use of public domain and creative commons images for illustrations. I've employed something similar here, and let's see how it goes. I'm aiming to post something every day.

---

### The night sky is increasingly dystopian

https://www.vox.com/science-and-health/2020/1/7/21003272/space-x-starlink-astronomy-light-pollution

I must admit I hadn't really heard about Space X's Starlink satellite project until recent Twitter excitement about seeing a cluster of the satellites overhead in the UK.

The plan is to place 12,000 satellites in low-earth-orbit to provide Internet access to remote areas of the planet. They will be visible for a number of hours after sunset, so even though we observe them during night-time, sunlight is still hitting them and reflecting down to us.

Astronomers around the world have concern about their impact on their observations. For casual night-time observers, there is potential for them to disrupt our clear view of the stars; they may appear with a similar magnitude to the surrounding stars, and there will be many of them in sky at any one time.

Apparently SpaceX has taken this concern onboard and is looking at ways reducing the albedo (reflectivity) of the satellites so that they will be less visible. Some may argue the positives of global connectivity especially for people living in remote areas. For me this looks like [electronic colonialism](https://en.wikipedia.org/wiki/Electronic_colonialism), and if other companies decide to compete with similar projects, then how can this be sustainable without filling low-earth orbital space with junk?

---

### Hugo

https://gohugo.io/

Hugo is the static site generator software I'm using to the manage this site. I love static site generators, they really help to put you into the mindset of World Wide Web first-principles and simplicity. Hugo converts template files together with content written with Markdown syntax into static HTML files which you can upload to a web server without the need for server-side programming or databases, and the front-end is as simple as you want it to be.

I'm using it with [Emacs](https://www.gnu.org/software/emacs/) for text processing, [Git](https://git-scm.com/) for version control and some simple [Bash](https://www.gnu.org/software/bash/) scripting for deployment.
