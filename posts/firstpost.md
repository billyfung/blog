---
title: Trying something new
description: Moving deployment and blog design
date: 2019-10-31
tags:
  - tech
layout: layouts/post.njk
---
## New set up

Trying something new and moving to serverless deployment. Should make it easier to blog more and keep things a bit more tidy. Design of the blog will be continual work in progress. Especially porting old blog posts over...

Ideally I wanted something that was easy to use, but also flexible and allowed me to learn something new. The [previous version](http://billyfung.github.io/) was using the [Hugo](https://gohugo.io/) framework, which is really quick for building static sites. I had a blast playing around with it but wanted to try something new. I still believe it's a great option for creating a new site quickly. Maybe it was just me that didn't explore enough of it's potential

Currently this layout is done using [11ty](https://www.11ty.io/) and then hosted by [Zeit](zeit.co). Zeit essentially does serverless builds for you, and you can connect it to a repo.

This simplifies my workflow by 1 step, since I don't have to build myself. Now I just push a markdown file to the repo and Zeit hooks will build and deploy, saving me the issue of forgetting to save and build. 
