---
type: post
comments: true
date: 2009-11-13T08:44:07Z

tags:
- Linux
title: Setting gnome-shell as the default window manager

wordpress_id: 3424
---

Gnome Shell will be the new window manager in Gnome 3, but it can be used in the current version of Gnome by installing the gnome-shell package, and running 'gnome-shell --replace' in a terminal.

To have Gnome Shell as the default window manager, setting the WINDOW_MANAGER environment variable won't work in Gnome 2.28. Instead you need to install 'gconf-editor' using your package manager, then go to:

/desktop/gnome/session/required_components

and set the 'windowmanager' key to 'gnome-shell' instead of 'metacity'.
