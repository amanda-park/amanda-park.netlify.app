---
layout: post
title: "What I Wish I Knew About R Sooner"
date: 2020-11-22
tags: [career] 
---

I was officially exposed to the programming language R when I enrolled in my graduate program in 2017. Three years have passed, and now I feel much more comfortable navigating R than I did when I first started. The way I learned R was very bumpy, and looking back there were a lot of ways I could have improved and expedited developing my skills in the language. I figured I'd write about this for anyone also interested in becoming proficient in R.

## Use the Tidyverse for Data Wrangling

When I was in my graduate program there wasn't a huge emphasis in manipulating data files to be in a format ready for analysis. Often we were just using simulated data or perfectly cleaned datasets and testing our competencies in certain modelling approaches. 

However, there was one professor that regularly gave us data that was messy in some way. At the time, I hated it because it led to a lot of extra work to complete assignments. In reality, the datasets he gave weren't really that messy at all compared to real-life data, and if I had known how to clean and manipulate data through the tidyverse package in R, it wouldn't have taken long at all to do that step of the assignment.

The best place to learn how to use the tidyverse is easily [R for Data Science](https://r4ds.had.co.nz/). What makes learning R great is that there recently have been a lot of nice online textbooks that have come out that teach both the basics and advanced concepts, so it's usually pretty easy to pick up on how to do certain things. 

## Use R Markdown Documents

In my graduate program, there was the expectation that your work was to be presented in a LaTeX file. This encouraged writing all code in plain R scripts and then transferring the results to be turned in via a LaTeX PDF. 

Given that I am not in academia for my career, this proved utterly worthless as a workflow for doing assignments. Further, it got me into some bad habits coding-wise, so frequently my code (while it was functional) was a pain to follow logically. 

If I had used R Markdown from the start and just submitted files that way (though I'm not sure if my program would have allowed it), I would have saved a LOT of time. I had to screenshot way too many outputs from R and insert them into LaTeX, but R allows you to embed both numeric outputs and images into an exported PDF and/or HTML file. Further, since Markdown is much easier to format and understand than LaTeX, writing up assessments on assignments would have been much easier. 

In my current job, I don't create reports or assessments through R Markdown - I mostly just use it as a way to organize my coding thoughts so it's easier for others to follow along. And I'm now spoiled by R (well, R Studio's) ability to handle R Markdown files in general compared to Python, because no matter what, Spyder and Jupyter Notebooks can't compete with what R Markdown has to offer. 

## Modularize Your Code

Okay, this isn't anything specific to R, but something that is not emphasized nearly enough for anyone who learns how to code in R. Being primarily a language for statistical analysis, a lot of pure software developers don't use R, and so the majority of users (though this has gotten better in recent years) instead write code that isn't intended necessarily for reusability.

I was guilty of this in grad school. I wrote code ad-hoc for assignments basically all the time, and it became a habit to just copy-paste code when assignments had overlapping uses. Each question in an assignment was different enough that the process couldn't be standardized in any meaningful way. 

Now that I've been learning about software development and best practices associated with that, I realize just how wasteful and inefficient a lot of my previous code was. I've been learning about how Python is an object-oriented programming language, and while it's not natural for me to think about coding things in classes just yet (especially in R, since classes are much different there), I now see obvious opportunities to make my code more reusable for future asks. I've learned how to properly make my own functions and (most importantly) make them general enough to be reusable for a variety of different situations. 

## Use Tidymodels For Modelling

For a lot of machine learning assignments I received in grad school I had to delve into a lot of different packages in R in order to successfully complete the assignment. It was a headache to manage all those different packages, and for the longest time scikit-learn in Python had the distinct advantage of at least being all in one place to read documentation about completing specific types of analyses.

That is no longer with the development of Tidymodels. Tidymodels is a standardized framework that builds in best practices for creating and tuning machine learning algorithms. It's flexible enough to work for both classification and regression problems, and includes most of the popular machine learning algorithms you would want to use for your analysis. 

If you use R in your day to day workflow at all, I highly recommend using Tidymodels. An online textbook called [Tidy Modeling with R](https://www.tmwr.org/) is currently still in development, but covers the basics.

(For what it's worth, I've also heard good things about [mlr3](https://mlr3.mlr-org.com/) from people at work, but I have not had an opportunity to fully explore it yet. It seems like once it's fully developed that it will be a great resource to use.)

## Conclusion

There's still plenty of smaller things I wish I knew about using R early on, but that touches on a lot of the main points. I was lucky enough to learn about ggplot and using R Studio as an IDE very early on, so I never struggled to find out how great those things were, but have rather come to appreciate their capabilities more as time has progressed. Hopefully this is helpful for anyone looking to further develop their R skills in the future!

