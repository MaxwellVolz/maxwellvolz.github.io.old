---
layout: post
title: How Jekyll Works
---


### Jekyll Build Process

1. Changes are made to a repository on Github ([Example](https://github.com/MaxwellVolz/maxwellvolz.github.io))
2. Github Pages compiles a new build of the repository and publishes the new site

The key thing to note is **the repository contains the files necessary for Github Pages to compile the site**.

---

### Repository Structure

~~~~~~
.
├── _config.yml
├── _data
|   └── members.yml
├── _drafts
|   ├── hack-the-world.md
|   └── making-a-milly.md
├── _includes
|   ├── footer.html
|   └── header.html
├── _layouts
|   ├── default.html
|   └── post.html
├── _posts
|   ├── 2018-11-03-github-pages.md
|   └── 2018-11-05-how-jekyll-works.md
├── _sass
|   ├── _base.scss
|   └── _layout.scss
├── _site
├── .jekyll-metadata
└── index.html # can also be an 'index.md' with valid front matter
~~~~~~

Make note on the **_config.yml** at the start and  **/_posts** directory.

---

### _config.yml

Set options for Jekyll in this file. 
~~~~~~
# Example:
name: Max Volz, Dude
markdown: kramdown
permalink: /blog/:year/:month/:day/:title
timezone: America/Tijuana
~~~~~~

* **name**: name of site
* **markdown**: flavor of markdown [link](https://github.com/commonmark/commonmark/wiki/markdown-flavors)
* **permalink**: how Jekyll parses the name of your */_posts* into links
* **timezone**: time formatting [link](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)

---

**All** of the config settings can be found [here](https://jekyllrb.com/docs/configuration/options/).

---

Typical options
~~~~~~
theme: 
~~~~~~
* theme


link to more options

---

### /_posts



### Next Steps
1. [Learn more about Markdown](/2018/11/04/markdown)
2. [How Jekyll works](/2018/11/05/how-jekyll-works)
3. **[Setup local development environment with Docker](/2018/11/06/local-jekyll-with-docker)**
