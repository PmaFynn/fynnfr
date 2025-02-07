---
#TODO: Rename to real title e.g. On bookmarking
title: 'Work in progress'
#TODO: set correct date
date: 2025-02-07T20:23:13+02:00
tags: ['blog']
# weight: 1
# aliases: ["/first"]
author: "Me"
# author: ["Me", "You"] # multiple authors
hideAuthor: true
showToc: false
TocOpen: false
#TODO: set false if finished
draft: false
hidemeta: false
comments: false
#TODO:use real description once finished
#description: "How I manage my bookmarks"
description: "As of yet this post constitues a work in progress though I sincerly hope that it will make more sense than Jocye's Finnegans Wake."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: true
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: false
ShowPostNavLinks: false
ShowWordCount: false
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---
I employ two distinct ways of managing my bookmarks.
The first is reserved for my essential/active/frequent (or whatever one might
call these) bookmarks and the second is used for--well, you may guess.
Lets start with the first class.

## How I use my essential bookmarks

This method is rather primitive but works exceptionally well. You just keep
your bookmarks (i.e. links) in a plain textfile. However, without the second
component, ingredient you could say, you might, as I expect, be
rather distrustful regarding the benefits of such a method.

Ofc you don't just store your bookmarks in a textfile and then manually
retrieve them when needed. I would not write this post to call attention to
such a method so do not worry.

Furthermore, it should be obious that I did not come up with this myself but instead adapted it from [Luke Smith](https://youtu.be/d_11QaTlf1I?feature=shared) though I doubt that he was the first to come up with it.

Well, assuming you haven't stopped reading to watch *Luke Smith's* video
instead, you might be wondering what the secret ingredient is. It is a
little (15.94 KB download) but amazing program called
[dmenu](https://tools.suckless.org/dmenu/). It "is a dynamic menu for X[^1],
originally designed for dwm. It manages large numbers of user-defined menu
items efficiently" or to use
[archLinux.org's](https://wiki.archlinux.org/title/Dmenu) slightly less minimal
explanation "dmenu is a fast and lightweight dynamic menu for X[^1]. It reads
arbitrary text from stdin, and creates a menu with one item for each line. The
user can then select an item, through the arrow keys \[*crtl+n/p* work as well\] or typing a part of the
name, and the line is printed to stdout. dmenu_run is a wrapper that ships with
the dmenu distribution that allows its use as an application launcher".

For the purposes of this post the first part of dmenu's functionality is more important while most people, I reckon, know it for the second, i.e., as an application launcher (esp. for window managers).

``bindsym $mod+i exec --no-startup-id sh -c 'xdotool type "$(grep -v "^#" ~/mega/bookmarks/bookmarks | dmenu -i -l 50 | cut -f2)"'``

### Benefits:

So, what are thea actual benefits I experience by doing this?

The main benefit, I would say is the ease of migrating to a new browser. What
do I have to do to continue using my bookmarks? Nothing. Another big plus is
that this works not only as bookmark for browser but for anything really. I can
use it in the terminal (sure, there are aliases &c. and I do not actually use
it in the terminal but I could) or I can save a system prompt for LLMs I
particulary like; I also experience no migration barriers here then when
migrating to another LLM provider. It's is a regular textfile. That's it; hence
it is of rather small size which, I will admit, is no game changer but
attractive nonetheless. I will further admit that a comphrensive setup requires
some initial effort (though not much; especially in the times of LLMs) but from
that point onward you are good to go forever basically. Depending on your setup
it will get setup automatically on a new device as well. Moreover, this
requires not account anywhere whatsoever.

### Drawbacks:

Tbf, I have no clue if this works on Windows. Well, it certainly does not with dmenu and even if it works it will probably be a hassle to set up.

### Extensions:

You can obviously extend this even further by adding more common bookmarking tool functionalities like, for example, being able to automatically add the current url to the bookmark file (I do not do this bc I have no need. Doing it manually keeps me kind of mindful of not filling up my bookmarks).

## How I use my non-essential bookmarks

Raindrop, dont know what much to say about this other than it is open source which, btw. dmenu is as well ofc.

- sync/copy textfile to cloud storage via rclone

[^1]: It is to note that X is, hopefully quite obviously, not refering to the new domain of twitter but instead, I admit that this might not be as obvious, to the X Window System (X11), a graphical display server that enables GUI applications to run on Unix-like operating systems. 
