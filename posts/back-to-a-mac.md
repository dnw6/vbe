---
title: Back to a Mac
description: Switching back to a Mac after a decade on Windows
date: 2024-03-12
tags:
  - mac
  - windows
layout: layouts/post.njk
---

I recently switched to a Mac, after almost 10 years of using Windows devices as my primary work machines. I'd used Macs before, in other jobs, and and my personal laptop is a Mac, so I'm no stranger to them, and in all honesty, it's felt like coming home after a decade in the wilderness.

That said, I have had to do some tinkering to get {% footnoteref "mac-spec" "A 2023 14 M2 MacBook Pro, 16GB RAM" %}my new machine{% endfootnoteref %} set up how I like it, so I thought I'd detail that tinkering here. In no particular order.

## The TinkerList

* Downloaded [Arc](https://arc.net/) as my primary browser. I'd been keen to give Arc a go, but hadn't been able to as it wouldn't run on my Windows 10 machine, or my ancient personal Mac. So far I've loved it, it feels like a great new paradigm for how browsers could and maybe should work.

* Set the dock to auto-hide, and removed most of the items from it. It currently looks like this:

<img class="article" alt="A screenshot of my macOS dock, showing shortcuts for Finder, System Settings, Safari, Arc, Chrome, Firefox, Figma and Slack" src="/img/my-dock.png" rel="lazy">

* Installed Git, mainly so I could clone the repo for this site, and deploy it via Github/Netlify. This meant installing xcode and homebrew from the command line, which is always vaguely stressful. And I'd forgotten about having to do all that defining path stuff, so it took me a while to get everything up and running, but it's all good now. There could definitely be better documentation around this though, as you quite quickly hit "computer says no" issues that take a bit of googling to figure out.

* Installed the [Raycast launcher](https://www.raycast.com/). I used to be an enthusiastic [Alfred](https://www.alfredapp.com/) user, but thought I'd give the main alternative a try. It was pretty straight-forward to get set up, and now I love it and use it constantly. For opening apps, files, folders, accessing my clipboard history, but my favourite thing is the widows management (one thing Windows does much better natively), which lets me easily resize windows, or move them between different displays. I've configured keyboard shortcuts to make this even quicker, so I just have to hit e.g. _option + left arrow_ to ping a window to or from my second monitor. I also really like some of the extensions, the Spotify one is great, to quickly see what's playing, or search for something to listen to directly in the Raycast interface.

<img class="article" alt="A screen recording showing the window resize functionality of the Raycast launcher app" src="/img/raycast-demo.gif" rel="lazy">

* Installed the [Bartender 5 app](https://www.macbartender.com/), to help tidy up what appears in my menu bar and when. I'm still on the free trial but will probably end up paying for this app, it's really handy.

<img class="article" alt="A gif animation showing items in a macOS menu bar showing and hiding based on a mouse click" src="/img/my-menu-bar.gif" rel="lazy">

* Installed the [One Thing menu bar app](https://apps.apple.com/us/app/one-thing/id1604176982), a tiny but brilliant app that lets you add a single task to your menu bar. For when there's one thing that you really need to do that day.

* Changed the cursor repeat speed. The system preferences didn't let me set it to move as fast as I would like, but [this incredibly helpful website](https://mac-key-repeat.zaymon.dev/) lets you preview different timings, and then gives you terminal commands to run which let you speed things up quicker than the standard UI allows. I'm very happy to have my cursor zipping along through text nice and fast now, just how I like it.

* I have a bluetooth mouse that I like, but when I first started using it there were problems: 

    * it was janky and slow, especially the scrolling
    * I couldn't set the scroll wheel on my mouse, and the scroll direction on the trackpad to be different. I like the natural scrolling setting on the trackpad, but that feels weird and wrong on the scroll wheel on a mouse. But macOS doesn't let you set these individually (it looks like you can, but the setting is linked, so e.g. changing it in mouse settings also changes it in trackpad settings). 

* So far, so annoying. But I guess other people have come up against similar issues, as there are quite a few apps that promise to fix them. I went for [Mac Mouse Fix](https://macmousefix.com/), which not only gives you specific control over scroll direction for your mouse, but also somehow magically fixes a lot of the slow, janky scrolling and interaction I had before installing it. I'm still on the free trial, but I'll happily pay the $2.99 when the trial ends. Although it is a bit aggrieving that a third party app is necessary to do something as basic as using a mouse.

* Bought a [folding stand](https://www.amazon.co.uk/dp/B09WNH5ZT9?psc=1). Just a cheap Amazon Basics one, but seems to be doing the job so far, and I like how small it folds up, making it easy to bring into the office or wherever.

* Bought [a (small, cheap) dock](https://www.amazon.co.uk/dp/B0BR3M8XHK?psc=1). Mainly so I could plug the USB A receiver my mouse needs into something. But also nice to be able to plug the hdmi into it, and so have less cables trailing out of the laptop itself. Slightly regretting not getting one that could do the power as well, but not sure what the deal is with docks and the magsafe power connectors.

* Bought the [Cleanshot X app](https://cleanshot.com/) for screenshots and screen recordings, both things I create multiple times a day. Pretty impressed with it so far, it's quick, user friendly, and seems to do everything I need it to.

I think that's all the tinkering I've done so far. I'm sure there will be more.

<hr>

A quick shout-out to [Kitty Giraudel](https://kittygiraudel.com/) for the [Eleventy Footnotes plugin](https://www.npmjs.com/package/eleventy-plugin-footnotes) I've used on this post, and will no doubt use in many others. It's pretty much out of the box, I just added a pseudo element using this character: ⇣ to differentiate footnote links, and added:

>`scroll-behavior: smooth;`
>`scroll-padding-top: 120px;`

to my css, just to make jumping back and forth feel a little nicer..

<hr>
