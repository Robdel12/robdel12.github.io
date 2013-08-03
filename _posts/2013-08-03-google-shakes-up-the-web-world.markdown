---
layout: post
title:  "Google shakes up the web world"
date:   2013-08-01 22:34:40
categories: thoughts, web technology
---
![Google Chrome](/img/blog-images/google-chrome.png)

Today, kids, is *exactly* why you should never rely on vendor prefixes in your code.

[Google announced their shake up to the web world today.](http://blog.chromium.org/2013/04/blink-rendering-engine-for-chromium.html) Google is Forking WebKit and will be building their own rendering engine called Blink for Chrome. Their reasoning is that Chrome uses a different multi-process architecture than other WebKit. From Google:

>However, Chromium uses a different multi-process architecture than other WebKit-based browsers, and supporting multiple architectures over the years has led to increasing complexity for both the WebKit and Chromium projects. This has slowed down the collective pace of innovation - so today, we are introducing Blink, a new open source rendering engine based on WebKit.

Opera will also use Blink, an interesting move since Opera announced it will be ditching Presto and using Webkit.

The current web landscape looks like:

* Internet Explorer uses Trident
* FireFox uses Gecko
* Safari uses Webkit
* Chrome/Opera will use Blink
* Almost ALL mobile browsers use webkit (Android uses a fork of webkit on mobile and samsung forked it. Making it a fork of a fork - we'll be lucky to see updates from samsung on this.)

## What does this mean for WebKit?

That is the first thing that comes to mind for me. Does it mean WebKit will fall by the wayside? I don't think so, but It does mean someone will have to pick up the work that Google has been doing for them. The graph below shows all the companies that commit to WebKit and their frequency.

![Commits to webkit](http://www.robert-deluca.com/wp-content/uploads/2013/04/commits.png)

So, who is going to fill Googles void? I can't answer that -- fully. I can tell you that Apple probably won't pick much up. They've put Safari on the back burner. I mean, they haven't even released Safari 6 for windows.

Who knows what this means for us developers, but like [Andrew Volk](http://twitter.com/andrewvolk) says:
>"I would hope the Chrome team handles the transition with great consideration since they're breaking the 'if it isn't broke…' rule."

We can only hope. What do you guys think?

**Let the browser wars begin... again!**