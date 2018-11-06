---
layout: post
title: Github Pages with Jekyll
---

Transform your plain text into static websites and blogs.

### What is Jekyll?!

Jekyll is a simple, blog-aware, static site generator for personal, project, or organization sites. Written in Ruby by Tom Preston-Werner. Thanks Tom!

### Why are we using Ruby?

Why not? Learning new stuff is fun! There is definitely alternatives for creating a static sites on Github *but* recently I've been crushing on markdown. Also, heavy integration with Github Pages.

### Markdown hmm?

Yeah. It's **hot**. The beauty of Markdown is its ease of use. [Single Page PDF Cheatsheet](http://packetlife.net/media/library/16/Markdown.pdf)

I use [Boostnote](https://boostnote.io/) daily for organizing my notes and documentation. It makes me feel like that girl in junior high with the 30-pack of highlighters and color-coordinated binders for every class. Epic.

Also shout out to [Dillinger.io](http://dillinger.io) for making my readme files not suck for the past few years. Nowadays I just copy the markdown from Boostnote, but Dillinger.io remains an exceptional product.

### What if I think Markdown sucks?

You might. People don't like all sorts of things. Don't worry. *Maybe it's not for you.*

### It is? Rad. Let's see how it works.

Jekyll's build process works like this:
1. Changes are made to a repository on Github
2. Github Pages compiles a new build of the repository and publishes the new site

The key thing to note is **the repository contains the files necessary for Github Pages to compile the site**.

# Graphic showing repository folder -> Github -> Github Pages Compiler -> site.github.io

### Run it locally!

[Keep going](/2018/11/05/local-jekyll-with-docker) to learn how to set up your local development process using Docker!
