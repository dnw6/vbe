---
layout: layouts/page.njk
title: About Me
templateClass: tmpl-post
eleventyNavigation:
  key: About Me
  order: 3
---

* I am a designer/front end developer
* I work at [Angel Solutions](http://www.angelsolutions.co.uk)
* In the past I worked at the [Ministry of Justice](https://mojdigital.blog.gov.uk/), and [The National Archives](https://nationalarchives.gov.uk)
* [This is my twitter account](https://twitter.com/hiccup)
- - - 

### I made three New Year's Resolutions in 2020

* Buy some new glasses (been meaning to do this for nearly a decade)
* Complete a Couch to 5K running program
* Start a blog (again)

*Hence this site.* Starting off with a really basic theme, plan is to slowly make it look... less basic. No rush though, is there?

**2021 update**
* <span class="text_small">Still haven't bought new glasses.</span>

**2022 update**
* <span class="text_small">Bought new glasses. But the dog chewed them up the other day. So now I need to buy another pair.</span>
* <span class="text_small">As of August 2022 I have completed 26 of the 27 runs in a Couch to 5k running program, and successfully run over 5k a couple of times.</span>

<ul>
{%- for post in collections.music -%}
  <li><a href="{{ post.url }}">{{ post.url }}</a></li>
{%- endfor -%}
</ul>
