---
title: 'Why I am using RSS and you should too'
date: 2025-01-16T20:23:13+02:00
tags: ['blog']
# weight: 1
# aliases: ["/first"]
author: "Me"
# author: ["Me", "You"] # multiple authors
hideAuthor: true
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Why I ditched algorithmic curated feeds and you should, at the very least, consider doing the same"
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
# cover:
#     image: "/home/fynn/projects/hugo/fynnfr/static/movies/dontLikeCover.png" # image path/url
#     # alt: "<alt text>" # alt text
#     # caption: "<text>" # display caption under cover
#     # relative: false # when using page bundles set this to true
#     hidden: false # only hide on current single page
---
What a title huh? I figured that is how one starts a blog post. Get the readers attention etc. etc.

I am assuming you have no clue what RSS is. If you do; [here is my feed!](https://fynnfr.org/blog/index.xml)

If you do not, here is a small intro:

## What is RSS (Really Simple Syndication)?

RSS (Really Simple Syndication) is a user-controlled way to follow online content, fundamentally different from modern social media platforms and email newsletters. Think of it as a decentralized news feed without ads, algorithmic manipulation, or corporate control.

Unlike email newsletters where you share your address with publishers (risking spam and data selling), RSS follows a "pull" rather than "push" model. An RSS feed is simply a text file on a website containing chronological posts, similar to a traditional newspaper format.

You choose an RSS reader application--there are many options available with a good few being open source--which then retrieves content only from the feeds you explicitly subscribe to.
The websites can not push content to you; you control what you see.

While RSS was widely popular about 15 years ago, many users switched to commercial social media platforms.[^1]

![Google Trends of RSS](/blog/rss/googleTrendsRSS.png)

However, there's renewed interest in returning to this simpler, more user-controlled system (well, according to [What is RSS](https://ncase.me/rss/) anyway; can't really see a spike in google trends; prob just a vibe the orginal author is getting from their bubble. However, it *should* definitely make a bigger comeback. Tough, I doubt it will happen). A similar technology called Atom exists alongside RSS, and modern reader apps support both formats.[^2]

## Why should you use it?

Did this not do the trick already?

Ok. Ok. Lets get out the disadvantages first. I do not wanna trick you into something. 

While RSS is used by most sites, some social media sites (i.e. twitter, instagram) make it quite difficult to get a working RSS feed.
There are still workarounds for twitter and instagram. However, it will require either some money to get a premium RSS service such as [rss.app](https://rss.app/) or some trickery. I will not go into the specifics here.

Wouldnt it be nice if people just go back to personal blogs. Nowadays that does not even take much effort to set up and you can do whatever you want with it. People would then, instead of following you on instagram, just subscribe to your rss feed.

Youtube, Reddit and some other social media pages on the other hand offer it quite easily. In the case of youtube you just use the regular channelid and you are good to go. Reddit allows you not only to subscribe to specific subreddits but allows you to specify search terms inside a subreddit, only subscibe to the top posts, only subscribe to posts with not images etc. etc.

### Look and feel

So how does this RSS feed look then? Well, the following image might actually be a turnoff for some but do not worry there are more graphical RSS-readers out there.[^3] I am just using [newsboat](https://newsboat.org/), a terminal reader since I like it quite minimalistic and it comes with vim-bindings which I love.

![How my RSS feed looks](/blog/rss/rssColage.png)

I can also sort via tags and search throughout all my feeds.

![Tags I use](/blog/rss/rssTags.png)

[^2]: Main source of the past section: [What is RSS](https://ncase.me/rss/)

[^1]: [Google Trends of RSS](https://trends.google.com/trends/explore?date=all&q=RSS&hl=en-US)

[^3]: For example the following three RSS readers. At least one has an app so you can use it on your phone (there are prob 100+ apps tough. So don't worry if you do not like that one in particular):

    ![Feeder](/blog/rss/feeder.png)

    ![Feedly](/blog/rss/feedly.png)

    ![Inoreader](/blog/rss/inoreader.png)
