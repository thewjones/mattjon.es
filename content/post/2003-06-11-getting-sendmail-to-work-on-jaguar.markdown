---
type: post
comments: true
date: 2003-06-11T16:00:00Z

tags:
- Uncategorized
title: Getting Sendmail to Work on Jaguar

wordpress_id: 719
---

[OS X](http://www.apple.com/macosx/) has, inbuilt, a piece of software called [Sendmail](http://www.sendmail.org/). It's one of these powerful programs that reside within the inner gubbins of OS X which can be made to do all sorts of powerful things using nothing else but the command line… if you're a [UNIX](http://www.geek-girl.com/unix.html) wizard that is (and I most certainly am not).



	

As its name implies, Sendmail is a tool for working with email. If you open a terminal window, you can type _'mail matt@frownland.com'_ followed by a subject and body text (adding a line-break and '.' at the end) and your email will be sent. Well that's how it should work anyway, because Apple - apparently, for reasons of security - have stopped Sendmail from working in Jaguar (it works up to 10.1.4). Now why is this a problem? Why can't I leave the UNIX nerds to worry about how they're going to send their emails and get on with using good old Mail.app? Well, it's a problem if, like me, you're using your Mac to learn about [PHP](http://www.php.net).



	

[Mail()](http://uk2.php.net/manual/en/ref.mail.php) is a function used to send email from within a PHP application. On machines running UNIX or its derivatives (OS X included), this function uses Sendmail to handle any emails that are sent from a PHP script. This is configured in the php.ini file with the line:



	

sendmail_path = /usr/sbin/sendmail -t



	

However, even with this path properly set, the mail() function will not work because of the problem with Sendmail. What's most annoying is that no error messages accompany the problem, so you're left completely in the dark when the test email fails to appear in your Inbox.



	

The solution lies in doing a bit of reconfiguring of Sendmail and the instructions to do this can be found in this [O'Reilly article](http://www.macdevcenter.com/pub/a/mac/2002/06/07/sendmail_1015.html).



	

If you're wondering why I've written this technical - admittedly dull - post, it's because I've spent all day trying to find the solution to this problem and if I can make someones life easier by publishing this information for [Google](http://www.google.com) to index, then I'm glad to have posted it.



	

Now… chimps.
