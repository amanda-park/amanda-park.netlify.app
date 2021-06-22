---
title: What I Wish I Knew About Python Sooner
author: Amanda Park
date: '2021-04-27'
slug: python-programming-tips-tricks
categories: []
tags:
  - career
  - data-science
featured_image: 'https://res.cloudinary.com/teepublic/image/private/s--TwCcIoc_--/t_Resized%20Artwork/c_fit,g_north_west,h_954,w_954/co_000000,e_outline:48/co_000000,e_outline:inner_fill:48/co_ffffff,e_outline:48/co_ffffff,e_outline:inner_fill:48/co_bbbbbb,e_outline:3:1000/c_mpad,g_center,h_1260,w_1260/b_rgb:eeeeee/c_limit,f_jpg,h_630,q_90,w_630/v1520050660/production/designs/2416585_0.jpg'
description: 'Some tips and tricks I wish that I knew when I started learning Python for data science years ago.'
---

A companion post to my "What I Wish I Knew About R Sooner" post, this one is similar in content with specific strategies and technologies for working effectively in Python.

## Plotly Is The Best Visualization Tool

One thing that I really struggled with in regards to using Python was its comparatively lackluster visualization options. Matplotlib and Seaborn are certainly functional plotting libraries, but compared to R's ggplot2 the visualizations were not up to snuff.

That's where Plotly comes in. Plotly is a multi-platform library that supports JavaScript, R, and Python. In R, Plotly can seamlessly wrap around any ggplot object and make it an interactive plot, which makes it incredibly convenient to use. In Python, there is a low-code plotting option called plotly.express that can use for a similar effect, but there's also the functionality for building more complex plots layer by layer. 

Plotly is also convenient because you can borrow themes from other common plotting libraries and have them applied to your plots by changing one parameter. For standardizing visualizations between R and Python, Plotly has been a lifesaver. (For a project our team tried using PlotNine for standardizing visuals, and it was clunky.)

In fact, I've found Plotly so nice in Python that I'm developing a [library](https://github.com/amanda-park/easyplotly) which saves the plot configurations for the ones used most frequently in my current role.

## Object Oriented Programming Isn't *That* Scary

Coding in an object-oriented programming manner in R is far from intuitive. There are multiple class structures to choose from, and more often than not you can get by with putting your reusable code in a function and be fine.

Admittedly coding in functions also works in Python, but since it's known as an object oriented programming language, open-source "Pythonic" code will follow the OOP structure more frequently. The first time I was exposed to it in Python code I found it foreign. It seemed needlessly complicated and clunky for most data science workflows.

However, implementing a class-based structure in certain situations can be beneficial. Something that's now obvious to me after working in a larger organization is the importance of code sustainability and reusability. By programming in a standardized format like OOP, that organization makes it easier for others to follow and work with your code. It's not necessarily fun (at least to me) to write code in such a manner, and sometimes it just makes a simple data science ask overly complicated. But for code that you expect to reuse, the benefits can make restructuring your code worthwhile.

## Documentation is Easy with Sphinx

I was turned on to website code documentation for large-scale projects by a current colleague. Normally the tedium of writing down what you did and why would grate on me in projects, and I was always frustrated that Python didn't have an equivalent of R Markdown to do work in. (I know Spyder is somewhat like R Markdown, but it's not as robust.)

However, Sphinx helps fill the gap as a companion guide. Creating documentation is as easy as having properly formatted docstrings and running a few lines of code on the command line. It makes worth both more reproducible and easier to remember if/when you have to go back to it. (And personally I think readthedocs is a bit less finnicky than using pkgdown, R's equivalent. But your mileage may vary.) 

## Conclusion

Overall, sharpening my Python skills over the past year has been very rewarding. I still prefer using R for statistical projects and would rather leave Python for deep learning and natural language processing asks. But both languages can certainly get the job done.