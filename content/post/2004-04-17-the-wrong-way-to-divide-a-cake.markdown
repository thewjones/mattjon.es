---
type: post
comments: true
date: 2004-04-17T14:15:00Z

tags:
- Uncategorized
title: The Wrong Way to Divide a Cake

wordpress_id: 431
---

This week's issue of [A List Apart](http://www.alistapart.com) has an article entitled [Let them eat cake](http://www.alistapart.com/articles/eatcake/) which explains how to break down long articles into easier to digest chunks using Javascript and the DOM. While it may be well coded, backwards compatible with Javascript disabled browsers and have some use for certain applications, I don't think it's an approach - especially as demonstrated in the [final example](http://www.alistapart.com/d/eatcake/final.html) - that should be encouraged, and I certainly take issue with the claim that it makes the content more accessible and useable.



	

It seems to be using Javascript to replicate the basic function of the browser; to request a page of information when a link is clicked. In my opinion, this creates more problems than it solves; spoofing separate pages within a single HTML document breaks the back button, and each chunk of content lacks its own URI  meaning that it can't easily be referenced. 



	

There's already a standard mechanism in place for breaking a long HTML page down into separate chunks: the internal anchor. These allow for sections of a page to be individually referenced and stored as a visited link, as well as keeping the back button working as it should.



	

I hate to read like [Mr Nielsen](http://www.useit.com) here, but unless I'm missing an obvious problem that this method solves, I think this is re-inventing the wheel, badly. I'm surprised at ALA publishing this. 
