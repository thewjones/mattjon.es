---
type: post
comments: true
date: 2003-01-13T08:49:00Z

tags:
- Uncategorized
title: Running The Gimp on OS X

wordpress_id: 795
---

Update [24/03/04]: Gimp 2.0 has been released, including a self-contained application bundle for OS X. [Get it here](http://gimp-app.sourceforge.net/)



	

[The GIMP](http://www.gimp.org/) (GNU Image Manipulation Program) is a piece of software similar to Photoshop but with one big difference, it's _free_ and _open source_. For many years, it has been **the** graphic / image manipulation tool on the Unix and Linux platforms and because it has been constantly in development over this time, it is as feature-rich [if not quite as slick] as Photoshop. After Apple launched [X11](http://www.apple.com/macosx/x11/) [an X Window system based on XFree86] on OS X, I decided to get The GIMP running on my Mac. Here's how to get it running:



	

**Disclaimer:** The following instructions are the result of a bringing together of information from various web sources. I cannot guarantee that these instructions will work on your setup as they represent the method I used to get The Gimp to run successfully on my Mac. By following these instructions, you are doing so at your own risk and I am not personally responsible if anything goes wrong! 



	

An overview of requirements:



	


	
  * [Mac OSX 10.2](http://www.apple.com/macsox/)

		
  * [Apple Developer Tools](http://developer.apple.com/tools/)

		
  * [Fink](http://fink.sourceforge.net/)

		
  * [Apple X11 Public Beta](http://www.apple.com/macosx/x11/) [including the X11 SDK]

		
  * A spare afternoon

	

	

Instructions:



	

  


  1. If you haven't done so already, install Developer Tools CD that came bundled with OS X. The disk image is also available to download from the [Apple Developer Connection](http://www.apple.com/developer/) website [requires free registration].



	

  2. Download and install Apple X11 - [http://www.apple.com/macosx/x11/download/](http://www.apple.com/macosx/x11/download/) [41.4 MB].



	

  3. Download and install the X11 [Software Development Kit](http://www.apple.com/macosx/x11/download/) [4.0 MB - Download on bottom right of page]



	

  4. Download the [Fink 0.5.0a Binary Installer](http://prdownloads.sourceforge.net/fink/Fink-0.5.0a-Installer.dmg?download) [11MB] and double-click on the 'Fink 0.5.0a Installer.pkg' to install Fink.



	

  5. After the installation is complete, open a Terminal.app window and type the following command: "_sudo pico .cshrc [return]_". This will open a text editor with the new .cshrc file. NB. sudo requires you to enter your Mac's administrator password.



	

  6. In the editor, type the following line: "_source /sw/bin/init.csh_".



	

  7. Save and exit Pico by pressing _[control-0], [return], [control-x]_. Then close the terminal window.



	

  8. Open a new terminal window and type: "_sudo fink scanpackages [return]_"



	

  9. Then type: "_sudo apt-get update [return]_"



	

  10. Then: "_sudo apt-get install gimp [return]"_. This downloads and installs the GIMP binary and it takes a while.



	

  11. Go to the Applications folder and double-click on the X11 icon. This will start the X Windows environment.



	

  12. From the X11 menu, select 'Applications > Terminal' . This will open xterm.



	

  13. At the prompt, type "gimp".



	

  14. After being asked a few simple questions by the GIMP set-up program, the application will launch. Enjoy!
  





	

Remember that The GIMP is a UNIX application designed to run on X Windows, so don't expect it look as slick as Aqua. Also, Apple X11 is still in Beta so there are a few interface quirks here and there. 
