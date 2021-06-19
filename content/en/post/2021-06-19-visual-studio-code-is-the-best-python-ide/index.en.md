---
title: Visual Studio Code Is The Best Python IDE
author: Amanda Park
date: '2021-06-19'
slug: []
categories: []
tags: 
  - career
  - data-science
featured_image: ''
description: 'My long and arduous journey of finding the RStudio equivalent for Python is now over.'
---

Python is seen by far across the industry as the most important programming language to know for doing data science. It has flexibility for being used for both general programming purposes and data science (as opposed to R, which was built for statistical computing first and foremost).

However, because Python was built as a general programming language first, I always found it frustrating to navigate the various clunky integrated development environments (also known as IDEs) that existed and were compatible with the language. Compared to the robust data-science focused development of RStudio, Python's options always left me with enough pain points with my workflow that I'd rather develop in R over Python when given the option.

That all changed when I found out how wonderful Visual Studio Code is. Before I get into the benefits of Visual Studio Code, I'll discuss some of the other IDEs I tried using and the various frustrations I ran into using them:

### Jupyter Notebooks

This is the most common IDE choice you'll see others use when trying to learn data science. It uses the Anaconda framework, which comes with some basic data science libraries like Pandas included, and you can set up different environments for working on various projects. All files are saved with the extension of .ipynb. 

__Pros:__

* A notebook is split into chunks. That is, you can a chunk of text comments (written in Markdown) alongside your code to explain what's going on.
* Code chunks in Jupyter Notebooks are pretty good at automatically showing any visualizations you may be working on (relative to working in .py files, anyway).

__Cons:__

* You simply can't work in .py files; if that's what you need, you will need to open another IDE to develop in.
* Code versioning is a nightmare using .ipynb files - while it's easy to see differences in code with Git using R's equivalent R Markdown format (.Rmd), you don't get that flexibility updating code in a Jupyter Notebook.
* There's no enforcement of best coding practices in Jupyter Notebooks, so it's very likely your code will look ugly and be organized inefficiently by the time you finish any analysis. 

In general, using a Jupyter Notebook is okay for exploratory analysis or creating tutorials, but it's hardly the ideal option for an end-to-end data science project.

### Spyder

This IDE wishes to be what RStudio is to R. Spyder is touted as the data science IDE for Python, and looking for something as robust and similar as RStudio as possible, I shifted over to this tool as soon as I got tired of wresting with Jupyter Notebook's pain points. Spyder comes installed with Anaconda as well as an alternative IDE option, but can also be installed separately from the Anaconda framework.

__Pros:__

* Looks like RStudio. For creatures of habit, this can be a plus. 
* It allows you to explore variables in your environment like RStudio, and that is not something that is present when you're working with a Jupyter Notebook.
* Pane for viewing data visualizations easily. Also very similar to RStudio, and something I much appreciated.

__Cons:__

* Does not support .ipynb files. I know I just mentioned some of the flaws of using Jupyter Notebooks for data science projects, but RStudio supports .R and .Rmd files. You can *sort of* recreate chunks of code in a .py file in Spyder, but it's clunky.
* I've run into random crashes using Spyder. Others I've talked to haven't had issues like I have with that, but it certainly isn't as stable of a program as I'd prefer.

### The Other Ones I Tried

I also tried a few other Python IDEs over the past year as I got frustrated with the buggy Spyder experience. These included:
* PyCharm
  * A traditional Python development IDE. It enforces coding best practices, which I appreciated, but was not built with data science in mind, so exploring data frames and variables was a headache. 
* JupyterLab
  * A next-gen replacement to Jupyter Notebooks apparently. I tried using it briefly and it didn't really ease any of my Juypter Notebook related pain points.
* RStudio 
  * Yes, it's actually trying to integrate and allow Python use natively too. However, it's still far too early in the process to be a stable solution. Might be viable in a few years as a legitimate competitor for a Python data science IDE.


## Visual Studio Code

Coding in Python with Visual Studio Code wasn't always great. Over the past 2 years a lot of love has been given to Visual Studio Code and Python integration. The labor of love shows with a vastly superior Python IDE.

__Pros:__

* Easy access to a function's docstrings. The amount of time I had to waste opening webpages to look up official documentation for function syntax has been greatly reduced by being able to hover over a function and easily see what arguments it takes. It's honestly even nicer than using RStudio, where you can still need to type ?function_name to get the documentation to pop up.
* Handles both Jupyter Notebooks and .py files. Say goodbye to swapping between two different IDEs just to work with one or the other.
* Swapping Virtual Environments is super easy. Rather than have to load a specific virtual environment from Anaconda when you open your IDE, you can simply choose on the fly to swap which environment you're working in. Even R doesn't make it that simple. 
* Encourages best software development practices, including:
  * Code linting
  * Docstrings for functions (can be automatically done with an extension called Python Docstring Generator)
  * Git integration
* **Intellisense!** Not having to write out everything by hand is a huge time saver.
* Oh, and you can code in other languages too - it supports JavaScript, HTML5, and many others.

__Cons:__

* As far as I can tell, getting visualizations in a pane in VS Code like RStudio/Spyder isn't easy to do. But that can be adapted around by other means, so it's a minor pain point.

## Conclusion

I promise this isn't any sort of advertisement for VS Code, but rather a sigh of relief at finding an IDE that eliminates almost all of my current Python development pain points. I encourage you to not make the same mistakes I did waffling around in inferior development environments for years and simply start off with the best tool for the job.