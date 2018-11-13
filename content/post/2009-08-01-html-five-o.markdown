---
type: post
comments: false
date: 2009-08-01T12:08:41Z

tags:
- Development
- Media
- Web
title: HTML Five-O

wordpress_id: 2911
---

At last, I've finally knocked this site into a shape I'm happy with. You'll find no crufty div soup round here. It's all [HTML5](http://en.wikipedia.org/wiki/HTML_5) goodness and it works on IE8 and IE7 using Remy Sharp's magic [HTML5 enabling script](http://remysharp.com/2009/01/07/html5-enabling-script/).

I found HTML5 to be a bit odd at first, but as I started experimenting with it, the simplicity and meaningfulness of HTML5 mark-up started to sink in. The best way to think of the new elements is something like this:



	
  * use <header> and <footer> in the obvious places, this negates the need for <div id="header"> and <div id="footer">

	
  * use <section> for the main sections of the page eg. <div id="content">

	
  * use <article> where you would have <div class="post">

	
  * use <aside> where you would have information related to an article, eg. <div class="date">

	
  * use <nav> for your navigation links


Then, instead of using IDs and classes, you use CSS selectors to select parts of the document tree to style. I found the W3C's [table of CSS3 selectors](http://www.w3.org/TR/css3-selectors/#selectors) invaluable for this. I've mainly used CSS2 selectors for compatibility with IE and older versions of Firefox.

I've also made use of the @font-face selector to embed [Museo](http://www.josbuivenga.demon.nl/museo.html) font for the heading styles. There's a good list of free fonts available for embedding on the [Web Fonts Wiki](http://www.webfonts.info/wiki/index.php?title=Fonts_available_for_%40font-face_embedding).

I must give credit to [Croc Camen](http://www.camendesign.com) and [Alex Gibson](http://www.alexgdesign.com) for their inspiring work with HTML5. I haven't had this much fun with web design in years.
