---
title: What I learnt building this site
description: Setting up a blog using Eleventy
date: 2020-04-14
tags:
  - fed
  - webdev
  - learning
layout: layouts/post.njk
---
New-ish year, new blog. I thought I'd kick it off with some thoughts on what I learnt setting up this site.

- - -

I'd wanted to have a play around with [Eleventy](https://www.11ty.dev/) for a while, so this seemed like a good opportunity.

After a couple of false starts, this site is (for now, pretty closely) based on the [Eleventy Base Blog](https://github.com/11ty/eleventy-base-blog) starter repo. 

An earlier incarnation was based on based on the [Hylia starter theme](https://hylia.website/), but after a fair amount of noodling around with it, I decided it was a bit over-engineered for my needs. My needs being a *very* simple blog. The json design tokens were cool and all, but I never figured out why all the classes were wrapped in square brackets, and I could only get the site to build if I changed a template file (as opposed to e.g. a scss file). I daresay I config'd it wrong somehow, but in the end it had more bells and whistles than I needed. I may well revisit Hylia, most likely after I've done this [Learn Eleventy From Scratch](https://piccalil.li/course/learn-eleventy-from-scratch/) course in the coming weeks.

The site is hosted on [Netlify](https://www.netlify.com/). Setting this up was mind-bogglingly easy. Just clicked a button, connected with my Github account, waited for 20 seconds, and there it was, an actual site at a temporary url. Felt almost magical.

