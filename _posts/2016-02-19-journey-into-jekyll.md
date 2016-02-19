---
layout: post
title:  "a journey into jekyll."
date:   2016-02-19 17:30:00 -0500
categories: jekyll
---

As this is the first entry in this blog, it seemed fitting to discuss how it was built: using [Jekyll](http://jekyllrb.com/).

![jekyll](/assets/images/jekyll-logo.png "Jekyll")

Jekyll is a really powerful tool for generating static sites using markdown or html.
It integrates wonderfully with GitHub Pages, and allows rapid generation of sites (like this one) with very little effort.

As primarily a PC user, however, I quickly came to realize Jekyll doesn't officially support developing on a Windows machine.
After drying my tears, I found all was not lost. The [Jekyll documentation](http://jekyllrb.com/docs/windows/) for Windows is sparse, but does direct you in the direction of a nice installation guide for [Running Jekyll on Windows](http://jekyll-windows.juthilo.com/). This will get you started with the ruby gems for Jekyll
so you can be up and running locally in no time. It is worth noting that you no longer have to worry about enabling a syntax highlighter such as Rouge or Pygments since
Rouge now comes standard in Jekyll 3. So if that works for you, you can skip the final steps of that guide.

Once you have Jekyll installed, I found a nice guide for running your site locally over at the GitHub docs on [Setting up your Pages site with Jekyll](https://help.github.com/articles/setting-up-your-pages-site-locally-with-jekyll/#running-jekyll). It describes how to get Bundler installed and how to start up
your Jekyll app with automatic file watching and site-regeneration with the `listen` gem. Really good stuff.

With Jekyll running my site, it was just a matter of learning the syntax. Luckily, Jekyll has no fancy language you need to master, or complex design methodologies to adhere to. Jekyll offers you a conventional [project structure](http://jekyllrb.com/docs/structure/) and an easy to use and understand [variable syntax](http://jekyllrb.com/docs/variables/) to create beautiful layouts, reusable components, and quality content--all in the comfort of your favorite [templating language](http://jekyllrb.com/docs/plugins/#converters-1). Jekyll utilizes Sass out of the box, which also makes styling your site a breeze. 

Depending on when this post is viewed, this site may look very different. As I dig more into Jekyll, I am constantly learning new tricks to spice up my layouts and content. Look out, Mr. Hyde, Jekyll is taking over.
