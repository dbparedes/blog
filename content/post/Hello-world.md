+++
title = "Hello world"
date = "2016-11-06T00:21:13-04:00"
subtitle = "AHORA SI"
banner = "/img/banners/fake-marketers-fake-traffic.jpg"
tags = ["ipsum"]
categories = ["social-media", "marketing", "web-development", "aaaaaa"]
socialsharing = true
nopaging = false
totop = true
+++

I’ve made the decision to take control of my feeds. I want to know how
many users are reading my blog via syndication so I’ve decided to move to
feedburner. The migration will be seamless for all readers.

<!--more-->

Additionally, I’ll be able to provide syndication via email as well.

How to Migrate from [Drupal](http://www.drupal.org "Drupal") to [FeedBurner](http://www.feedburner.com/ "FeedBurner")
---------------------------------------------------------------------------------------------------------------------

These directions are written with Drupal in mind, though the approach
used would work for pretty much any system. All we need to do is 3
simple steps.

### 1. Move the feeds location to a hidden location for feedburner to read

In drupal this is really easy. Just create a url alias from rss.xml to
another feed name like “FeedBurnerHiddenFeed”

