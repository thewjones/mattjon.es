---
type: post
comments: true
date: 2003-01-30T18:37:00Z

tags:
- Uncategorized
title: Trackback

wordpress_id: 784
---

I tried to figure out Movable Type's [Trackback](http://www.movabletype.org/trackback/) a few months ago but I gave up because a) I didn't quite understand it and b) I found the way it works to be a little intrusive. [Tom Coates](http://www.plasticbag.org) has come up with a pretty elegant [solution](http://www.plasticbag.org/archives/2003/01/building_trackback_into_plasticbagorg.shtml) by modifying the output of the CGI script and including it into the bottom of each post. I've done something similar using MT's [Standalone Trackback](http://www.movabletype.org/docs/tb-standalone.html) and PHP; if the post has no Trackback pings, then nothing gets printed, which is a pretty transparent solution I think. The Trackback URL can be seen in the article [permalink](http://www.ballofstringtheory.com/article/152).
