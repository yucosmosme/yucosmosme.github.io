---
title: "jekyll minimal mistakes: posts by category"
# excerpt: "basic css flex"

categories:
  - Dev
tags:
  - jekyll
  - github
  - github blog
  - minimal mistakes
  - posts by category
date: 2021-02-19 18:00
comments: true 
---

> In need of catogorizing posts, I added categorizing settings to my jekyll - minimal mistakes theme.

### 1. add md file

1-1 add three md files in `_pages` directory : 

`category-archive.md` : categorizing by category
`year-archive.md` : categorizing by year
`tag-archive.md` : categorizing by tag

Contents in each file will be as following:

```
# category-archive.md
---
title: "Posts by Category"
layout: categories
permalink: /categories/
author_profile: true
---
# year-archive.md
---
title: "Posts by Year"
permalink: /year-archive/
layout: posts
author_profile: true
---
# tag-archive.md
---
title: "Posts by Tag"
permalink: /tags/
layout: tags
author_profile: true
---
```
These files are also in `docs/_pages` directory. You can copy and paste from there.

Of course, you don't have to create all 3 pages - just select what you need.

### 2. change _config.yml file

2-1. change _config.yml file as below: this will enable to open categorized pages.

```
category_archive:
  type: liquid
  path: /categories/
tag_archive:
  type: liquid
  path: /tags/
year_archive:
  type: liquid
  path: /year-archive/
```

### 3. Adding the categorized pages to the navigation bar

3-1. If you want to add the categorized pages to the navigation bar, add as below to `_data/navigation.yml` : 

```
# main links
main:
  - title: "Categories"
    url: /categories/
  - title: "Archive"
    url: /year-archive/
  - title: "Tags"
    url: /tags/
```
