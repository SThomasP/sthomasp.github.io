---
layout: post
title: "Hey Tumblr, Fix Your RSS Feeds"
date: 2018-05-21
author: Steffan
categories:
- Tumblr
- RSS feed
- GDPR
---
There's a good mix of blogs, webcomics and other oddities that I follow online. For most of this stuff, I track of them by subscribing to their RSS feed. This means every time one of these things update, I get a nice new article appearing in [Inoreader](https://www.inoreader.com/). From there its pretty easy to read the things that interest me, while filtering out the rest.
<!--more-->
At least, that's how it's supposed to happen.

Unfortunately for me, as well as everyone else who uses RSS, for any reason, the internet as a whole seems to have decided that RSS needs to be banished to annuals of history, in favour of mobile and desktop notifications. The latest self inflicted casualty in this war against RSS seems to Tumblr. Let's talk about it.

Tumblr recently updated their privacy policy, as is expected. With the [GDPR](https://gdpr-info.eu/) coming into effect most sites are sending out their newly updated privacy policies. Tumblr also is now presenting everyone with their [new privacy policy](https://www.tumblr.com/privacy/consent) as the first thing you see when you first load any Tumblr page without the correct cookies, including the RSS feeds.

So hey, guess why I'm a bit mad.

It's very hard to put trackers and such in an XML file, impossible if you're trying to meet the [strict specifications](https://validator.w3.org/feed/docs/rss2.html) of an RSS feed. So not only is Tumblr probably not tracking the bot that scrapes one of the sites many, many RSS feed. Tumblr has also shut down any bot that attempts to do so, or only the ones operating in the area now affected by GDPR as it turns out.

I'm getting pretty annoyed at this general reluctance of sites to support RSS, its useful in a lot of circumstances. From listening to _[The Bugle](http://feeds.feedburner.com/thebuglefeed)_ to making sure you've read the latest page of _[Customer Service Wolf](http://customerservicewolf.com/tagged/customerservicewolf/rss)_, feeds are cool.

I wouldn't complain if Tumblr were to replace their RSS feeds with [JSON feeds](https://jsonfeed.org/). Standards change, but the basic idea of having a feed that updates when the source publishes new content shouldn't, it's a good idea and one that I hope will be long supported.

So Tumblr, fix your RSS feeds.

