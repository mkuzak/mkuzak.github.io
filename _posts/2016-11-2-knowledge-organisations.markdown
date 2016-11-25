---
layout: post
title:  "How Learning works part 2. Knowledge Organisations"
date:   2016-11-2 13:39:00 +0200
categories: teaching SoftwareCarpentry
---
This is the second part of 7 part series discussing ideas presented in
[“How Learning Works: 7 Research-Based Principles for Smart Teaching”](https://www.amazon.com/How-Learning-Works-Research-Based-Principles/dp/0470484101).


In the second chapter of "How Learning Works" authors show that not
only what students learn but how they organise their knowledge has
profound implications on their learning. Knowledge can be organised
in ways that either do or do not facilitate learning, performance,
and retention.

Knowledge organisations of experts and novices are very different.
The former organise knowledge in a complex network that connects the
facts, concepts, procedures within the domain. The latter have not
yet developed such connected or meaningful organisations. They tend
to build sparse, superficial knowledge structures. The teacher should
not assume that students will organise new knowledge in a way that
she does. She should provide students with a structure for organising
new information. This structure should not only support the creation
of a high number of quality connections but also fit the task the new
organisations need to support.

# What are the actions a teacher can take to improve the way students organise their knowledge?

**Understand how you organise your knowledge.** This can be done by
creating a Concept map of the topic you want to teach. I find this
exercise very insightful. Often it shows me the gaps in my own
knowledge or makes me realise that connections I considered obvious
are not so obvious after all and much harder to explain. This will
push me to look for better more clear connections. I also try to
think of the connections with concepts outside of the topic.
Comparison of maps around different concepts may also show some
repeating patterns which can be very useful when teaching.

**Introduce knowledge organisations that support the way they will be
used.** If your goal is to introduce students to the data analysis,
do not only show the functions and operations that are used in the
process. Explain all the steps like data import, cleaning, reshaping,
visualisation and group operations accordingly. Point out why the
order of steps is important. Show how reshaping the dataset into the
`dataframe` will facilitate visualisation or what happens if one
visualises the dataset with errors or missing values. This will make
much easier for students to retrieve and apply new skills when faced
with the whole data analysis task.

Novices tend to organise their knowledge in silos, mirroring the way
it was presented to them. Using the same example as above, if you
teach those different steps of data analysis as separate lessons
without pointing out how they are interconnected you cannot expect
students to make the connections themselves. They may learn all the
necessary steps of data cleaning or all the different ways to
visualise them but may have problems performing the whole task. You
can emphasise those connections even more by presenting an outline of
the course and outlines of the lessons, pointing out how they fit
together. In Software Carpentry workshops each lesson has a list of
objectives. It is easy to skip those, but your teaching will have a
much higher impact if you take the time at the beginning of the
lesson and go through them. Even though I know that making
connections between different lessons is important, tend to forget
about it while teaching. I do make connections between concepts
explicit, for example between `head` in *shell* and `head()`
function in *R* or `filter` and `select` with *dplyr* and *SQL* but I
rarely take time at the beginning of the workshop to explain how all
the lessons fit together, draw a bigger picture. I think it is very
important thing to do.

**Presenting with contrasts and boundary cases** will allow for the
formation of more sophisticated knowledge organisations. For example,
when teaching `lists` and `generators` in *Python*, showing both the
differences and common features will help students understand deeper
how they work (especially generators, which I think are harder to
grasp).

Authors suggest asking students to draw concept maps at the beginning
and in an ongoing manner to monitor how their knowledge organisations
change. I think this not only helps teachers to see how students are
improving their understanding of the concepts but also gives students
time to process and organise all new information and transform it
into knowledge. As I mentioned in the previous post it's common to use
concept maps at the beginning of the DC spreadsheet lesson.
Unfortunately, there is not much time to do it more frequently during
the workshop.

Similarly to concept maps, **sorting different problems, concepts or situations**
into categories will help students establishing more robust knowledge
organisations and unveil cases when students focus on superficial
similarities instead of deep features.

# Summary

How students organise their knowledge has a great impact on how
efficiently they can use it. Teachers cannot assume students will
figure out efficient knowledge organisations and should help students
with this task.

There are few techniques or approaches mentioned in this chapter,
that I rarely use. I believe I can improve my teaching by taking time
in the beginning of the workshop to outline how all the lessons fit
together, what is the bigger picture. I also want to try out
introducing more use of concept sorting.

I'm curious what are your thoughts on knowledge organisations.
