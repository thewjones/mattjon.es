---
type: post
comments: false
date: 2009-11-27T12:15:17Z

tags:
- Linux
- Web
title: Getting Typekit to work with Chromium and Namoroka

wordpress_id: 3518
---

[Typekit](http://www.typekit.com) really need to improve the way they do their user-agent detection. At the moment, it seems that if the user-agent-string doesn't contain either 'Firefox' or 'Safari', then Typekit won't work, even when the rendering engine is capable of rendering the fonts.

This isn't an issue for many. But it is if you're using a development build of a browser, or you're using a Linux distribution with a modified version of Firefox that, due to licensing restrictions, can't use the Firefox branding. In this case, the user-agent string will contain the development name of the browser, such as 'Shiretoko' or 'Namoroka'.

In Firefox, changing the user-agent string in about:config to 'Firefox' will solve this problem. In [Chromium](http://code.google.com/chromium/) (the development build of Google Chrome), you'll need to launch the browser with a command something like this:

`chromium-browser --user-agent="Firefox/3.5.5" --enable-remote-fonts`

Recent builds of Chromium now support @font-face, so you might not need the -enable-remote-fonts option.

Hopefully, Typekit will improve their browser detection by checking the rendering engine in the user-agent string, rather than simply the browser name.
