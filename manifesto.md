---
title: Manifesto
subtitle: My philosophy on design
layout: "page"
icon: fa-book
order: 2
---

The single biggest difference between projects completed in this class and projects I have completed in other classes
and my day-to-day life is that the creation of a project here keeps the farthest end goal in mind - the actual use of the program.
At times, a program I create has little need for this approach; a one-off script for smoothing some data might only be used by a couple
of scientists who don't mind typing a verbose command into their terminal, for instance. Thus, the end user has little to do with the product itself.

Or so I had always assumed. In this case, had I really thought about it, perhaps I would've seen the human element of the programs. Perhaps this human element doesn't really occur during the execution of the program itself, but in its development. Would it not be useful, even for a "one-off" script, to be able to extend it later? Why not follow a certain interface accross every such script? You could later combine them all into one. Perhaps the user is the programmer, in this instance, but I promise that programmers really are humans deep down, too. There is simply no way around it. Whether your program is written in C or is a fancy combination of whatever web tools are the fad that day (MongoDB I'm looking at you), your program is ultimately going to have to interface with humans. 


> your program is ultimately going to have to interface with humans


While valuable, this insight is also confusing. It is hard to generalize what creating programs with the user in mind really means. A mood board is hardly useful for my smoothing script, but could be invaluable in the creation of a mobile website. Nevertheless, there are certain takeaways that apply to both.


### Ideate with the true end goal in mind

While it is impossible to do anything without forming ideas first, the process of idation in the context of Human-Computer Interaction always seemed to follow a general pattern. The most interesting part for me was not throwing ideas at the wall, but instead the part that came immediately after: deciding who you're making the program for.

During the final project of the class, Design for Another World, my group and I were astonshed by the possibilities afforded to us by the rich world of VR. After throwing around several ideas and doing some quick research, we settled on creating a car purchase assistant. Initially, I assumed the obvious: we want to make this as enjoyable as possible for the user. While not wrong, this approach still misses something. If you're a software developer, who would you actually be designing software for in the most direct sense? Not the user, but the dealer. The dealer's interests, too, should thus be taken into account during the creation of the software.


### Consider the specifics

Now that you have determined your goals, it is time to consider what defines this project from others you have done before. I felt a jarring difference during the class between the design process during Design for Others and that of Design for Tension. The process for creating a website for a given demographic is fairly straightforward: you start with the visuals you think your demographic will find most enticing.

![Mood board for Design for Others](https://cdn-images-1.medium.com/max/1440/0*o49M6RvR3tCEoycH.)

Something like a mood board is perfect for this task. It gives you something to draw from during the creation of the site. Often times, gathering these sorts of resources can tell you what *not* to do as well. Occasionally, you begin attempting to use something and realize that something about it, perhaps the color or shape, simply does not fit with anything else you want to use.

![Flag of Worcester](https://cdn-images-1.medium.com/max/1440/0*qgRZfeT_Jd7CkdG5.)

Though the City of Worcester is doubtlessly important to the visitors of the Worcester Public Library, its flag and its, er, *dominating* color is hardly useful to you.

When you're creating a chat bot, however, things are quite different. You likely won't personally design the visuals the user sees. As a result, the mood you give off comes soley from the user's interactions with your bot. Does it seem abrasive, or helpful? Thus, it becomes important to find this sort of thing out.

### Use yourself as well as others

As important as feedback from others is (more on that later), you yourself aren't useless. After a long day of hacking, it can be very important to step back for a while so you can ask yourself for feedback later. I use the same strategy here as I do when writing a paper: don't try to create from scratch and edit in the same sitting. Perhaps you should sleep on it. After waiting a while, it becomes easier to let go of your biases and evaluate your project for what it is. Just because I spent a long time figuring out what what the chatbot should say to a student doesn't mean its reaction is actually useful. The next morning, I'll likely have to suck it up and delete some code, replacing it with something better.

An extremely common sentiment among the readings of the class was that the end-user often doesn't really know what they want, at least not directly. It is far easier to show someone something close to what they want and ask them to improve it than to get them to come up with ideas from scratch. Thus, despite your biases, you as the creater have something over a random user in your target demographic: you know the goal. Your own viewpoint is one of the most important to the success of any project. Use it well. That being said, you can't stop there.

### Ask someone else

Once you have something that you feel accomplishes your goal, it is time to ask some people who weren't involved with the project what they think. Ideally, you should put them in an environment where they will naturally go through the processes you are most interested in. From there, simple observation is the best approach. Watch the user interact with the program, and see where they get caught up. 


During Design for Understanding, I went through several phases of development trying to capture the effect of majoring in a STEM field on statistical unemployment rates. Having a bar chart with seventy distinct labels, one for each major, was completely uninteligable. However, distilling down to five-or-so categories, while far more visually pleasing, failed to show the truly important information.


![By category](https://cdn-images-1.medium.com/max/2000/1*VoztXDw66irODeKIlYz0UA.png)

Thus, I decided that perhaps each major could be shown, but the information could somehow be distilled. Instead of labeling each major, I left the axis blank and colored each bar: blue for STEM, red for non-STEM (or HELL for History, English, Language, and Literature as a high school teacher of mine was fond of saying). Meanwhile, the user could mouse over a bar to see what major it represented.

![All majors](https://cdn-images-1.medium.com/max/1440/1*BBsCUJIuufSqpcZBIcfcjQ.png)

I was fairly satisfied with this result, but after demoing it, realized that it could be confusing. It turned out to be difficult for people to discern what the actual message of the graph was. A statement like "notice how blue it gets below 4%" helped a lot.


