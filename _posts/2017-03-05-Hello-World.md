---
layout: post
title:  "Hello World!"
---

I finally took some time this weekend to finish setting this blog. This blog is powered by [jekyll](https://jekyllrb.com/) static site generator and it uses a modified [Hyde](http://hyde.getpoole.com/) theme for the layout. I find jekyll to be refreshingly simple. The config file is just a text file, the entire blog is version controlled, there's no need for a relational database and markdown for post formatting. This means I can just use my preferred text editor of choice (In case you were wondering, vim) to write and edit posts. This fits in really well into my workflow as I already use [Gollum](https://github.com/gollum/gollum) for my personal wiki.

I was initially considering setting this up on [Linode's](https://www.linode.com) new $5/mo instance but then my research pointed out that Github pages is also jekyll beneath the covers. I was looking for 
* Ability to setup a custom domain.
* An RSS/Atom feed.
* Support for categories and tags.

I learned that I could enable Atom feeds on Github pages by adding
```
gems:
  - jekyll-feed
```
to my jekyll config. With that, Github pages seems to fill in all my checkboxes so I decided to give it a go. I also setup my laptop with ruby and installed jekyll and github-pages gems so that I can preview blog posts before pushing them to Github. I still have to figure out how and if I should add the ability to add comments to posts.

I've been trying to learn the Go programming language for the past couple of weeks. I found many things to like and a few thing to dislike about Go while I was trying to implement the rsync algorithm. I plan to write about it soon.
