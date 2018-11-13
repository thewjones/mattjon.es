---
type: post
comments: true
date: 2002-01-31T17:39:00Z

tags:
- Uncategorized
title: Style Switch

wordpress_id: 1048
---

I've been waiting for someone build a site where the user can switch between completely different CSS designs rather than just switching between colours or font sizes, and [adactio.com](http://www.adactio.com) does just that. In terms of graphic design, I think we're really starting to see something happen with CSS driven web design and I sense that Chris Casciano's article [Your CSS Bores Me](http://www.ChunkySoup.net/opinion/boringcss/) has riled designers into pushing the limits of what is possible. Now that more people seem to be adding bitmap graphics to their CSS layouts, it's important to remember the whole point of using Style Sheets in the first place:  to separate style from content. So, if a graphical element of your site is part of the **styling** of the site, then define it in the stylesheet, for example:

    
    
    <br></br>#head {
    <br></br>background: url(../images/graphic.gif) 0 0 no-repeat;
    <br></br>}
    <br></br>

Alternatively, if a graphic is part of the **content** of your site, such as a photograph in a weblog, then put it in the HTML with the rest of the written content. The aim is to keep your information uncluttered and logically structured, without unneccessary graphics that should belong in the page's styling. A good way to monitor this is to add Tantek Celik's 'Toggle CSS Style Sheets' [favelet](http://www.tantek.com/favelets) to your bookmarks. This is a piece of javascript which strips the style sheet from your HTML document, allowing you to see what your page looks like without any styling information. If your page still looks good, is clear to read and easy to navigate around when the style sheet is disabled, you have designed your site well.  Visit waferbaby.com or glish.com and toggle the style sheets off to see examples of good mark-up design. 
