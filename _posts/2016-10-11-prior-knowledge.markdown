---
layout: post
title:  "How Learning works part 1. Prior Knowledge"
date:   2016-10-11 13:42:00 +0200
categories: teaching SoftwareCarpentry
---
This is first part of 7 part series discussing ideas presented in
[“How Learning Works: 7 Research-Based Principles for Smart Teaching”](https://www.amazon.com/How-Learning-Works-Research-Based-Principles/dp/0470484101).

In the first chapter of “How Learning Works” authors describe how
Students’ prior knowledge affects their learning. Its main message is:

> Students' Prior knowledge can help or hinder learning.

# Different Aspects of Knowledge

When prior knowledge is **activated**, **sufficient**, **appropriate**
and **accurate** it will facilitate learning. When it’s **inactive**,
**insufficient**, **inappropriate** or **inaccurate** it will have a
negative impact on learning.

We need to understand what those terms mean before we dive into practical
ways of improving the learning experience.

If a student cannot make the connection between prior knowledge and new
concept, this knowledge is **inactive**.

Sometimes there is some information lacking and the learner does not
have enough knowledge to grasp new concepts. It is important to
understand here that there are different ways of “knowing something”.
There is *declarative knowledge* — knowing **what** and **why** and there is
*procedural knowledge* — knowing **how** and **when**. For example, a student
may know what the unit tests are but have never written one.

In some cases, the knowledge we have seems to fit the new problem,
but in fact, it cannot be used in the new context, it is **inappropriate**.
For example writing an essay and technical documentation both require
writing skills but they apply different rules. Another example will be
when students proficient in one programming language try to apply same
approaches in newly learned language (*eg.* loops vs vectorised code).

When prior knowledge is **inaccurate** or **wrong** students may have
problems understanding new concepts because they will be in contrast
with what they already know. This can be very straight forward and easy
to fix. If experienced Python programmer indexes from 0 while working in R,
he or she need to be corrected and with time will make fewer mistakes.
It can be much harder to revise deeply held misconceptions. It can also be
hard to spot them since the student will be convinced she or he understands
the concept well.

# Assesment
Before the instructor can start teaching she has to assess both the amount
and nature of students’ prior knowledge. How can we gauge the extent and
of students’ prior knowledge? I will try to present some solutions based
on what the authors say and  how I think it fits with Workshops.


**Talk to the Hosts of the Workshop.** Learn about the background of the
students. What domain are they coming from? What are the datasets they
usually work with? Do they collaborate on the code they write? This
will help you get a beter grasp of students' background.

**Have Students Assess Their Own Prior Knowledge.** Self-assessment
designed well will allow you to tell if students have declarative
or procedural knowledge. Software Carpentry uses pre-workshops surveys
that students fill in before the workshop. The instructor should read
it carefully before the workshop.

**Administer a Diagnostic Assessment.** Having few short exercises
with different levels of complexity before starting the lesson will
help you gauge learners expertise.

**Use brainstorming or Assign a Concept Map Activity.** I found
those especially useful since they integrate well with the rest
of the lesson. We use those techniques in Data Carpentry spreadsheet
lesson when students come up with different problems with
spreadsheets by themselves and the result of this is the great start
for the discussion.

**Look for Patterns of Error in Students Work.** Paying attention to
what kind of mistakes learners make in exercises will help you grasp
better the state of understanding.

# What to do now?

Once we know what is the status of prior knowledge in the group of
learners we need to address those issues.

**How to Activate Prior Knowledge?** One way is to emphasise the
connection to previous or other lessons. When teaching Python
and showing joins in Pandas connect this to what students learned
in SQL lesson. Other is to use analogies from everyday life.
An example could be cooking recipe and Makefiles. You have to
be careful though to see and tell students when analogy breaks.

Lack of Necessary Prior Knowledge means you have to **adjust workshop
content** to get students up to speed. Since the experience may vary
across the group, it helps to pair less advanced students with savvier ones.

To help students **Recognise Inappropriate Prior Knowledge** highlight
the conditions of applicability. For example, not all data fit tabular
format or bar plot is good for presenting categorical data but not
relationship beteen two variables. Again show learners where the
analogies break down.

**How to Correct Inaccurate Knowledge?** The best approach is to let
student explain their reasoning. One of the methods we use during the
Workshops is to pair students for exercises and let them explain their
choice to a partner. Also allowing students to try out their newly
acquired knowledge through different exercises will help with reinforcing
new accurate knowledge.

# Summary

There are many good and bad ways students’ prior knowledge
may affect learning. Above I have explained what are the culprits and
solutions with some practical tips that can be applied id Carpentries Workshops.

I hope you found above post interesting and learned something new.
