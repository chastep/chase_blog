---
title: Helllllllooooo Middleman!
date: 2017-10-28 18:55 UTC
tags: blog, setup, middleman
---

[Helllllllooooo Middleman!](https://middlemanapp.com/basics/blogging/)

Thought I had to reiterate the title again. What can I say, I was pretty excited I got this thing up and running.

This was a test of Middleman's overall functionality and usability. There is a ton out there on how to actually build a blog. There are tons of ways to do it and it's all up to you which way you want to do it. 

Landing on Middleman was just a happenchance of me getting it working in the first place. I have plenty to learn in terms of its usability for hosting a legit blog. I hope I can look at the progression of using Middleman and come out ahead. If it only causes me misery I am sure I'll let y'all know.

So, here is a rough list of resources I found helpful in building the app from the floor up:

* [Middleman](https://middlemanapp.com/ "Middeman Homepage") => This is the legit website. I liked that the app itself was ruby gem. In April when I kicked this off I was on a Ruby kick given I had just finished DevBootcamp. Who doesn't like just running `gem install middleman` and having the install work done for you?
* There are tons of docs provided in the link above as well. Useful portions were:
  - 'Starting a New Site'
  - 'Directory Structure'
  - 'Build & Deploy'
  - 'Blogging'
  - 'Configuring Your Site'
  - All these were vital for propping up the site itself. Given I had only done this a handful of times before, it was a good challenge to try this in another environment.
* [AWS Guide to Adding Domain](https://docs.aws.amazon.com/AmazonS3/latest/dev/website-hosting-custom-domain-walkthrough.html) => After exploring the inner guts of Amazon Web Service (hope to write a post on this soon) I found this to be an easy to follow guide on adding my whacky domain name.
* [Styling a Middleman Blog with Bourbon, Neat, and Bitters](https://robots.thoughtbot.com/middleman-bourbon-walkthrough) => Even though I barely used anything thing in this article, I still found it extremely helpful. I know that my CSS is uber weak, so the evolution of the styling around this site is a main focus as it grows.
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links) => Most helpful markdown cheatsheet I have found. Since all Middleman blog posts are written in markdown, this was useful.
* [Google Fonts](https://fonts.google.com/?selection.family=Dosis) => A must to find a baus font. Still get lost in trying new ones out.
* [Middleman Setup Quick Tutorial](https://webdesign.tutsplus.com/articles/project-build-a-complete-website-with-middleman--cms-25429) => Didn't follow this word for word, but damn was it insightful and informative!
* [Jekyll](https://jekyllrb.com/) => Great comparison of another static site/blog app.
* [Middleman S3_Sync](https://github.com/fredjean/middleman-s3_sync) => This is a really cool gem that I use to automatically deploy my changes! A quick `bundle exec middleman build` followed by a `middleman s3_sync` gets my weird mind online in a flash!



