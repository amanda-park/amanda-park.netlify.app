---
title: Update! Changing Websites
author: Amanda Park
date: '2021-02-20'
slug: []
categories: []
tags: []
featured_image: ''
description: 'Pivoting from hosting on Github pages to Netlify - also talking about the new website design!'
---

Hi everyone! This is an update post. Previously, I have been hosting my content on [Github Pages](https://amanda-park.github.io/), but I have switched from Github Pages to Netlify for hosting my personal website. Github will still be used, but it will be reserved for hosting documentation only. 

The new link I will be posting content on is [Netlify](https://amanda-park.netlify.app/). This is the site you're on now! Everything probably looks different compared to before, so you're probably asking...

## Why Did I Change Websites?

Well, there are a couple reasons:

### The Old One Was Awkwardly Stitched Together

I had initially built a portfolio site roughly 2 years ago on using the github.io name after cloning a repo and messing around with the html and css. Roughly a year later I decided I wanted to add in a blog on top of that, which was deployed on Github Pages via Jekyll. These two things did not play well with each other and looked very different.

By putting everything under this new website umbrella, the look and feel of the website will be the same regardless of whether you're looking at my portfolio page or my blog. Further, maintenance in the future will be simpler now that all the code is consolidated.

### More Flexible Blog Options

I recently began reading an [online book about blogdown](https://bookdown.org/yihui/blogdown/) and realized how simple it was to build a website using the framework Hugo through R. Given how comfortable I am navigating R at this point, it didn't take long to set up and get this new website rolling. 

So far I've noticed Hugo is more flexible than Jekyll was. Many things I had to add to Jekyll manually (for example, tags) are handled innately by writing a blog post in Markdown. Adding images or other outside content is also much simpler. And by far the nicest benefit of writing posts in RStudio is through the blogdown package, posts will automatically update in the viewer pane as you save your progress. 

Overall, it's just super duper convenient.

### Netlify Is More Flexible than Github Pages

Github Pages is not a bad tool at all. Due to its convenient integration with pkgdown, it will still host any package documentation I create. 

But Netlify has more features that make it easier to maintain a general purpose website and blog. It was also far easier to set up a Hugo framework blog on Netlify compared to Github Pages, which uses Jekyll as a base for building webpages. 

## Conclusion

I've put in a redirect on the old portfolio page so people will arrive on this site rather than the original I had previously set up.

I look forward to continued posting on this new platform, and hope you stick around for the journey!
