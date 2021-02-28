---
title: 5 Things I've Learned Being a Data Scientist
author: Amanda Park
date: '2021-02-28'
slug: []
categories: []
tags: 
- reflections
- career
- data-science
featured_image: ''
description: 'Data science is considered one of the "sexiest jobs" of the 21st century. I figured I would throw my hat into the ring and describe what it has been like being a data scientist in healthcare for the last 18 months!'
---

Data science is considered one of the "sexiest jobs" of the 21st century. I figured I would throw my hat into the ring and describe what it has been like being a data scientist in healthcare for the last 18 months!

## 1. The Data Is (Usually) Ugly

In grad school, a lot of the datasets that my cohort worked with were relatively clean. They were canned datasets so there were no ambiguities about data definitions, and there were few, if any, missing values. (Well, outside the lecture where we were taught about missing values, that is.)

Real-life data isn't like that. Often a lot of work goes into just cleaning up the data so that it can be reasonably used for analysis. 

For example, being in a large healthcare system, data defintions aren't always clear nor consistent. When looking across different parts of the organization, a lot of work often goes into making sure defintions for data being stored "match". Much more emphasis goes into merging and maintaining those datasets than is ever discussed while in school.

Data is also generally not structured in the best format for analysis. You often have to structure the data so that it's appropriate for ingestion into an algorithm. This can be done via SQL or through programming language packages like the Tidyverse (for R) or Pandas (for Python).

In general, sometimes you're just a data janitor, not a data scientist. Perfect data never exists.

## 2. Storytelling is Key

When I was a teenager, I wanted to be a journalist. I dreamed of reporting on the biggest stories going on in the world and providing that information to regular citizens in an easily digestible format. 

After witnessing the 2008 recession and massive cuts to local newspapers, I decided against going down that path. But I ended up finding a career path where telling stories was still hugely important.

Humans are storytellers. Stories tend to stick in a person's brain more effectively and can persuade leadership to make appropriate business decisions with your statistical analyses.

You can certainly tell a person with pure statistical outputs what is going on; this was what was required of presentations that were given when I was in graduate school. However, unless you're surrounded by people with similar technical ability, the meaning will be drawn out and muddled. Leadership has *maybe* 15 minutes to consider what you're talking about, and odds are most of them think a pie chart is the best way to visualize data.

Data scientists are expected to communicate the boundary between analysis and actionable steps. You need to tailor your presentations to leadership to ensure that a cohesive and compelling narrative is being told. A story will motivate leadership to act; an analysis will just be "another meeting" to them.

## 3. Everybody Loves Python

Back in March 2020, the COVID-19 pandemic changed all our lives forever. Many tragically passed due to the disease, employment situations rapidly changed (whether it be working from home or layoffs due to a recession), and social distancing is now part of the social lexicon.

During this time, the data scientists on our team were expected to forecast how COVID-19 would impact our various hospital systems. Having no background in epidemiology, we did a lot of research into understanding how diseases generally progressed as well as noting what pre-existing models were doing for modelling the impact on hospital beds.

**Nearly all these models were built in Python.** 

Up to that point, I was almost exclusively an R user. This job didn't care whether you used R or Python, and a lot of previous analyses by former data scientists were done in R, so there wasn't much motivation to switch languages. The culture was set for using R, and early into my role I wasn't about to change that. 

I wasn't completely clueless about Python, because when I was job hunting I knew places generally preferred Python to R. I understood the basic syntax of Python and could do an ad-hoc analysis hitting up pandas and scikit-learn if I needed to. However, I didn't have an understanding of object-oriented programming and other Pythonic coding principles, so when these epidemiology algorithms were posted by computer scientists, it was very easy to get lost.

After a few months, we eventually went away from using open-source algorithms and developed in-house models built in R for forecasting hospital bed utilization. But that experience was a wake-up call for me. 

You don't just need to know how to code in Python with the basic data science packages (matplotlib, pandas, numpy, scikit-learn, etc) and crank out an analysis. *You need to be able to code in Python like a software developer does.*

Over the past few months, one of my professional development goals has been to fill those gaps and learn object-oriented design in Python. It's not been easy given that I don't have a computer science background, and it's very easy for me to still get tripped up by the various jargon. But I can already tell that my coding skills have improved by investing my time towards this. 

## 4. You Can't Know Everything

I know I just made a point above about knowing Python. Learning the language deeply is really the best bang for your buck you can make for your technical skillset as a data scientist.

But some job applications will list any tool under the sun that they expect a prospective data scientist to know. These can include the following:

* R
* Python
* SQL
* Julia
* SAS
* MATLAB
* Java
* Tableau
* Power BI
* Hadoop
* Spark
* Hive
* Excel
* Docker
* Git
* etc... 

And that doesn't even includ the specifics that might be expected of someone who knows that particular language. For example, if you know base Python they'll also expect you to know:

* Tensorflow
* Keras
* PyTorch
* Scikit-Learn
* NLTK
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Plotly
* etc...

And to be able to use those packages in Python appropriately you'll need the data science technical skills to understand these very broad topics:

* Data Preprocessing/Cleaning
* Data Visualization
* Predictive Modelling
* Supervised vs Unsupervised Learning
* Natural Language Processing
* Deep Learning and Neural Networks

None of those broader data science skills are easily picked up overnight. Further, to be a master in all of those languages above, it would take a long time. It's not feasible to know them all, and further, you don't **need** to know them all.

Obviously, knowing the theoretical concepts is critical. You'll need those with whatever language you choose, so don't skimp on that piece of things. As far as languages go, here's what I've settled on regarding data science programming in 2021:

* R for statistical analyses
  * I have 4 years of experience here and R is built for this. It feels wasteful not to use R for what it's meant for.
* Python for deep learning and natural language processing
  * Python is ahead of the game compared to R in this regard. I know you can build a neural network in R without any trouble, but Python gets the latest and greatest algorithms built for it first. Plus, see point 3.
* SQL for obtaining data
  * No matter what language you use, you'll need to pull data. Both R and Python can connect to ODBC sources for this.
* Git for version control
  * Again, no matter what language you use, being able to document and reproduce your code as the build goes along will be invaluable.
* Excel for the stupid simple stuff
  * It's true - even as a data scientist some things will be easier to just do in Excel. 
  
The rest of the languages and their usage depends on the company. For some of you reading, you may see no need to learn R, but for my current job knowing R is essential. 

Anyway, if you're searching for a data science job and get overwhelmed by all the "wants" in a job description, I recommend focusing on those I highlighted (prioritizing Python and SQL first) and the data science technical skills needed to use those languages effectively.

## 5. It's Satisfying Work

You tackle a bunch of unique and challenging problems as a data scientist. Different solutions are required depending on the use case, and that makes every day into the office a bit different than the last. 

The specific types of asks you get are going to depend on the field that you go into. Healthcare (my field) has different data science problems than being in transportation would, for example. 

But all the asks go towards bringing value to an organization that previously isn't able to extract meaning from the data that they're collecting. And I think that makes being a data scientist incredibly rewarding. 

# Conclusion

I know it's seen as a "fad" to be a data scientist due to the amount of people wanting to get their foot in the door in this career niche. I certainly see data science job duties evolving to require more software engineering skills in the future. But I don't think the career itself is toast. Data analytics is still a growing field, and while getting specifically into data science might be really hard, it's still possible to start off in a similar analytics role (like data analyst) and work your way up towards being a data scientist.