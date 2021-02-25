---
title: The resilience and longevity of a simple website 
description: A list of all the many ways I keep track of the things I need to do
date: 2020-08-06
tags:
  - design
  - dev
  - html
layout: layouts/post.njk
---

HTML, CSS and presentational JS (inc. JQuery and slider plugin(s))

No build process
* Repo is very portable, with no set-up to speak of. No npm install, no webpack config.

No tracking, analytics, social media embeds or cookies. No cookie banners. Downside is no idea about visitor numbers. But can get basic stats from server logs if needed.

Main wrapper width set as a percentage, so it still looks OK on bigger monitors than many people had in 2013.

Stripped down, minimalist design means it doesn't, imho, look massively dated.

Responsive - worked on a wide range of devices in 2013, still works on a wide range of devices in 2020.

It's not perfect. There are plenty of things I'd do differently now. 

* Old, potentially insecure version of jQuery.

* Text doesn't have enough contrast.

* Image definition could be better placed so it's more clearly associated with the image it describes.

* No explicit home link.

* Weird placement/text alignment of NPG link

* Could make better/more performant use of web fonts.

* Heavy use of IDs over classes

* No SSI or similar, so menu is hard-coded/duplicated into every page. But really, for the amount of times it's been amended, the time it takes to duplicate any changes is surely less than however long it would take to set up some form of templating and all that entails.
