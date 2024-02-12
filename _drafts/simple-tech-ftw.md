---
title: Simple Tech FTW
description: A post about why sometimes simple is best
date: 2024-01-29
tags:
  - html
layout: layouts/post.njk
---

Recently, someone I built a website for quite a long time ago got in touch and asked me to make some updates to the site.

I built the site in *2012* - that's pretty ancient, especially in web years. I built it using the tech I was familiar with at the time, which was hand-coded html, css, and a couple of jQuery plugins. No Sass. No JS framework of any kind. No build processes. It doesn't even have any includes or partials - if I need to update the navigation (which I've done precisely once in the last 12 years) I go into each of the half a dozen html files, and replicate the change in all of them. Efficient, DRY code? No. Robust, pragmatic code that is unlikely to break? Yes.

Obviously this kind of tech isn't suitable for most sites in this day and age. It's not scalable. The "developer experience" is poor. It's only really suitable for static content sites that don't get updated very often. But when it is suitable, God, it's a breath of fresh air. And because the site a) had a pretty minimal design, and b) was built [responsively](https://alistapart.com/article/responsive-web-design/), it still works perfectly well on phone, tablet and desktop sized screens.

And the delicious, if irritating irony was that I went to publish this blog post, which is an [Eleventy](https://www.11ty.dev/) site, hosted on Netlify, deployed via a Github repo, and what happened? It wouldn't deploy. I just got a generic error code on the Netlify dashboard, and had to spend significantly longer tracking down the issue* and fixing it than it took to write this post.

*Issues, plural, as it turned out. The Netlify <-> Github authentication had broken, and I had to update a whole bunch of NPM packages.
