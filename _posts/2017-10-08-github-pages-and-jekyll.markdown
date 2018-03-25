---
layout: post
title:  "The Idiot's Guide to Github Pages with Jekyll for custom domains"
date:   2017-10-08 15:12:29 +0300
tags: [tech, github, jekyll, blog]
categories: tutorial
---
1. jekyll new \<blogname\>; inside that folder, create a folder "docs"
2. initiate it as a repository 
3. in _config.yml add:
<code>
	exclude: - [CNAME]
	keep_files: [CNAME]
</code>
4. in config.yml add: destination: docs or (otherwise everytime you build you have to add <code>--destination ./docs </code> to your build command
5. add Gemfile and Gemfile.lock to gitignore. Add all. commit. push.
6. in Github settings, point github pages to docs
