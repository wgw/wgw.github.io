---
title: Setup with git and github
layout: post
categories: nuts-and-bolts jekyll
---

# Setup doc 
- https://briancaffey.github.io/2016/03/17/jekyll-tutorial.html
	- A couple of problems in this tutorial; mainly cloning the github site is a mistake.
- https://ndench.github.io/jekyll/setup-jekyll-on-github-pages
- https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll

# Recipe 
```
	(from .. folder = Jekyll folder)
	jekyll new wgw.github.io
	jekyll new wgw.github.io
	cd wgw.github.io/
	(bundle exec jekyll serve)
	git init
	git add .
	git commit -m "start"
	git remote add origin https://github.com/wgw/wgw.github.io.git
	git push -u origin master
```

# Markdown

- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

# Various

- popd, pushd

