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
description: "As of yet this post poses as a work in progress though I sincerly hope that it will make more sense than Jocye's Finnegans Wake."
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
call these) bookmarks and the second--well, you may guess.
Lets start with the first one.

## How I use (and manage) my essential bookmarks

This method is rather primitive but works exceptionally well. You just keep
your bookmarks (i.e. links) in a plain textfile. However, without the second
component, ingredient you could say, you might, as I expect, be
rather distrustful regarding the benefits of such a method.

Ofc you don't just store your bookmarks in a textfile and then manually
retrieve them when needed. I would not write this post to call attention to
such a method so do not worry.

Furthermore, it should be obious that I did not come up with this myself but instead adapted it from [Luke Smith](https://youtu.be/d_11QaTlf1I?feature=shared) though I doubt that he was the first to come up with it.

Well, assuming you haven't stopped reading to watch *Luke Smith's* video
instead, you might be wondering what the secret ingredient is. It is a small,
little (15.94 KB download) but amazing program called
[dmenu](https://tools.suckless.org/dmenu/). It "is a dynamic menu for X,
originally designed for dwm. It manages large numbers of user-defined menu
items efficiently"[^1] or to use
[archLinux.org](https://wiki.archlinux.org/title/Dmenu) slightly less minimal
explanation "dmenu is a fast and lightweight dynamic menu for X. It reads
arbitrary text from stdin, and creates a menu with one item for each line. The
user can then select an item, through the arrow keys or typing a part of the
name, and the line is printed to stdout. dmenu_run is a wrapper that ships with
the dmenu distribution that allows its use as an application launcher".

For the purposes of this post the first part of dmenu's functionality is more important while most people, I reckon, know it for the second part i.e. as an application launcher (esp. for window managers).

### Benefits:

- no migration barriers to other browser
- works everywhere really
- small file size
- relativly minimal setup required
- no account whatsoever required


### Extensions:

- write script that adds highlighted text to bookmark file




[^1]: It is to note that X is, hopefully quite obviously, not refering to the new domain of twitter but instead, I admit that this might not be as obvious, to the X Window System (X11), a graphical display server that enables GUI applications to run on Unix-like operating systems. 
