---
title: Duplicate and Delete Element how I love thee
description: The awesome usefulness of duplicate and delete element functions in browser dev tools
date: 2021-02-19
tags:
  - design
  - dev
  - html
  - devtools
layout: layouts/post.njk
---

![Screenshot of Duplicate Node function in Firefox dev tools](/img/duplicate-node.png "Duplicate node!")


I work on some very data heavy applications, and as such, always try to design and test for *Not Enough Data*, *Too Much Data*, as well as *Just The Right Amount of Data* (the last of these is always rarer than you assume).

The Duplicate Node and Delete Element options in Chrome dev tools (the same functions are called Duplicate or Delete **Node** in Firefox) are super-useful for this. Want to see how that list looks with three more items? Duplicate some of them. Want to see how that chart looks with one less data point? Delete one of them.

GFI goes here

It's a quick, lightweight way to manipulate what's in the [DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction). Yes, you can Edit as HTML and add, remove and edit anything you like. But that can be fiddly and time consuming. This isn't, and as such, I use these options every day, and I'm sure the pages I design are better and more robust for it.
