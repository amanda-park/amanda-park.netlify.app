---
layout: post
title: "What I Learned By Developing an App"
date: 2020-04-21
tag: reflections
---

During grad school, whenever I had free time I read many books about mental health. (Motivated by necessity - I was struggling to get by some days.) I learned a lot of useful information in these books that I felt would be useful to share with other people in some capacity. 

I also realized that getting the job I wanted right out of grad school would be challenging. I identify myself as a generalist over a specialist, so I figured that building an app would be a helpful review of coding outside the programming language of R, which I exclusively used in school. 

I then decided making an Android App was the answer. I would develop a guidebook that covered various mental health techniques for people to have on their phone when they needed it. Beyond hitting the aforementioned desires, it would also be a cool thing that I could tell others I built as well (both personally and professionally). If you want to check it out, you can download it [here](https://play.google.com/store/apps/details?id=com.amanda.mentalhealthguide).

## The Process I Followed

I started off researching the best tools in order to build this app. The first programming class I took in undergrad involved coding in Java, so when I saw that was an option to build an app with, I jumped on it. I learned pretty quickly that when you don't code in a language for a few years, it can take a while to knock off the dust and get comfortable using the syntax of the language again. 

Then I downloaded Android Studio. It's a powerful interface for developing apps, but I would not describe it as intuitive to a newcomer. There was a pretty hefty learning curve where I had to learn navigating the GUI and understanding both the formatting and location of files in an application.

I came across many different terms I had not heard before. Before building this app, I couldn't tell you what the difference between a fragment and an activity was. I didn't know anything about user interface (UI) design prior to this, and through trial and error I learned what kept the app both functional and fast. I would by no means say I made the app pretty (I am a stick figure artist at heart), but I was happy with how it turned out visually. 

## The Challenges I Faced

But before I became happy with how it turned out, I ran into a few major issues that I've realized are endemic to many projects. You may recognize some of these in your own experiences, and perhaps they are a rite of passage that all developers have to learn eventually. 

### Scope Creep

I almost let my initial idea for an app become so complex that it stopped me from completing it. My app ended up with far more content than I ever intended it to initially. When I first started building it I wanted to focus on having just a few things available for people, and to build on if I was interested later with new features.

That didn't happen, though. I decided that I should cover  more therapies and make the app more robust, which added to development time. An app that could have reasonably been completed months earlier wasn't because I decided I needed to tinker with it until it met my standards. 

In hindsight, if I had planned this app out more carefully rather than put it together as I went, I could have avoided this scope creep. Now that I have experience working in a large-scale organization, I have also seen scope creep affect other projects and believe that I am better equipped to resist the pull of a "bigger and better" result.

### Not Using Version Control

Yeah, I know. I can feel the glares coming through the screen. If you look in the GitHub repository of my code for this project, you'll see that there are old versions of files that are in there. However, I did not go out of my way to put them there. That only happened because Windows periodically backed up my save files, not because I went out of my way to do so.

(In newer versions of Android Studio version control is automatically built into the application. So perhaps I would have practiced better version control habits for reproducibility purpose had this feature been built in a year ago.) 

Anyway, the reason this was a learning lesson because I lost time and progress because I didn't practice good version control habits. At one point, my strings.xml file had its format altered, and my app because unusable as a result. It took hours to fix a change that, with proper version control, I could have just reverted to a previous version in a minute. Sometimes you just have to learn those lessons the hard way to realize their importance, I suppose.

### Not Commenting Well Enough

This one plagued me when I took breaks between working on this project. I was lazy with commenting what new features I added to this application and just assumed I would remember what I was doing months ago. Unsurprisingly, I regularly forgot what changes I made and had to spend time re-learning something all over again, when commenting would have saved trouble in the long run. 

It's embarrassing looking back how little I kept track of what every step of my code did, and one of the major lessons learned I took away from this project was to comment any future work thoroughly in such a way that I would not be confused when I looked back at it later on. (Thankfully when using R it's easy to use R Markdown files, and when using Python Jupyter Notebooks allows for Markdown and code chunks. So it's become standard practice when I have to code on the job for me now, to the point of seeming excessive to my colleagues.)

## Conclusion

Overall, I was content with how my app turned out. It was not a successful endeavor by traditional means (only my friends checked out the app), but I learned a lot of important lessons through this project, both in regards to coding and with building the discipline to pursue projects in the future (which I hope will help me stay consistent with this blog). 
