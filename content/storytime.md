---
title: "Storytime"
date: 2021-04-01T15:12:04+01:00
draft: false
---
# Story time!

Sarah is a postdoctoral researcher in an astrophysics group. She has been using research software and writing her own code to run and analyse simulations for years but not had much formal training. She wants to improve her coding skills and thinks the rest of her group would benefit from this too. She has heard someone at a conference talking about a 'Research Dugnad' so she emails them and asks for more information. She finds the [Research Dugnad repository](https://github.com/research-dugnads/dugnads-hq) is full of useful information on what one is and how to organise it!

## Preparation

Sarah emails her head of group Prof. Magnum, who is skeptical. Prof. Magnum learned to program computers with punch cards and feels very modern because they not call their code files ".f90" instead of ".f77". They do not see why students should share code and think it is a valuable learning experience for everyone to write everything from scratch. Sarah shows them some of the resources linked in the Motivation document, such as articles from Nature discussing the crisis of reproducible research and explains how version control can benefit the group, as well as  other activities that might be usefully done during their Research Dugnad such as making sure everyone's email addresses are visible on the University website, taking a new group photo including the incoming PhD students, and brainstorming ideas for the next funding round.

Having convinced Magnum to give it a try and even use some grant overheads to buy everyone lunch, Sarah contacts every member of the group to find a day in the next month when they would all be free. Since they are all living locally and there is no pandemic they decide to meet in person. Sarah also contacts the University's central Research Software Engineering group and asks if one of them could join the group for part of the session.

Inspired by the Turing Way's [Guide to Collaboration and Event Organisation](https://the-turing-way.netlify.app/collaboration/collaboration.html), Sarah books a meeting room that has flexible seating so they can decide what setup they want for the day, plenty of power sockets for everyone's laptops, and is close to an accessible toilet as one of the group has accessibility needs. She emails an outline plan for the day to the whole group so everyone knows what to expect and adds a questionnaire asking 3 things:

- What coding skills do you have that you could teach someone else?
- What coding skills would you like to learn?
- What is one problem you regularly get stuck on, bug you often encounter, or large issue you need help to solve?

The day before the event Sarah sends a reminder email with the times and room, and bakes some oat and pecan cookies (having checked no one has a nut allergy).

## On the day

Sarah invites her group to Meeting Room 203 for a 10:00 start which doesn't clash with her colleague's school run. She quickly introduces the idea of the day: we're collectively working on some of the small tools, fixes, and ideas that will make working with the group's code better. She reminds the group that this isn't about solving the big problems, and that we're all working on collective improvement so nobody should worry that their PI is looking over their shoulder and judging them.

To break the ice, they play a quick icebreaker game. Everybody gets stuck in to "astro-charades", even if Rashid's attempt to mime Cepheid Variable is a little difficult to interpret.

At 11:00, it's time for a teabreak, cookies and agenda building! Drawing from the unconference format of Collaborations Workshop, Sarah gives everybody three Post-It dots: small sticky circles. She's written the suggestions for tasks people had sent on large Post-Its, and stuck them to the walls. Each person gets to place their dots on the ones they'd like to do (or all three dots on one task if they think it's really important). As the group are doing this over their refreshments, they realise some of the ideas are related and choose to combine them along with their votes. Other new ideas get proposed, and they go up on new Post-Its and people transfer their dots.

After half an hour of this, voting comes to a close. The dots are counted, and the six tasks with the highest votes get selected for the afternoon session. To keep the mood light before lunch, Sarah asks the group - starting with Professor Magnum - to each relate a "code confession". What's a particularly bad piece of code you've written, or a catastrophic bug you introduced? The PhD students react first with confusion, then with hilarity, as Magnum shows them the small piece of choc ice stuck to a Fortran punch card that changed a 0 to a 1 and ruined a week long batch run. Then everybody else tells their stories, and everyone in the group realises that there are no superhuman coders to fear: everybody has their mistakes to share.

To keep the team energy up through lunch, they go to the refectory together. It's a rare treat for everyone, particularly the PhD students, to get to charge their lunch to the group's budget code.

They get back to room 203 at 1 o'clock, and agree to spend the rest of the afternoon working on the identified tasks. As it's a big group, they split into two teams which each take on three of the six tasks.

The team collectively agrees a cadence for these tasks: three quarters of an hour working, followed by a quick "show and tell" where they swap results before working on the next task.

Rashid, Colette, and Massimo take a look at the first task: introducing some automated tests using the [FRUIT](https://www.software.ac.uk/blog/2016-09-28-look-fortran-unit-test-frameworks) tool. Massimo is a research software engineer from the IT Services group, so doesn't know much about the astrophysics problems everyone is working on but is able to help get them going with unit testing.

The trio make some good progress, and quickly have a couple of tests started. They'd like to get the FITS subroutines tested but discover that the code isn't organised in a way that makes this easy. Addressing that would be too big a task to get done in the available time, so they make a note of it to work on later.

Meanwhile, Magnum, Sarah, and Nilam take on an important administrative task that has been languishing for ages. The group's page on the department website is incredibly out of date: Nilam's biography doesn't appear on it at all! They update the text, make sure all of the publications and conferences are listed, and create links to their collaborators in other institutions. There are some things that must be done by IT, like embedding YouTube videos with animations generated by their codes, so they raise those in the IT work tracker.

They carry on like this until 16:30. One team replaces some home-grown Python scripts with a module they found on PyPI. Another writes documentation and usage notes for the scripts that can't be replaced. Sarah then calls everyone back for the final group session. This is a retrospective, where she invites everyone to share what they enjoyed, what they learned, and what they will be carrying forward into the rest of their work. To collective astonishment, Professor Magnum accepts that he now understands the point of version control, and says he'll look out for training opportunities for the group. Massimo points out the [Software Carpentry](http://swcarpentry.github.io/git-novice/) course and says that the RSE group has a few Carpentries trainers.

## Afterwards

Sarah compiles the feedback everyone gave at the end of the session into a set of notes and adds them to the group Git repository as suggested tasks for next time they have a dugnad. She emails the RSE to thank them for coming along. They reply that is was very useful to get to know a bit more about their research area. They noticed that several people seemed to struggle with Git workflow and have decided to run a general course on this that will be advertised to the whole department.

Magnum later emails the group a funding opportunity for skill training and says he would support anyone who wants to apply for money to attend code-related courses now that he sees how much of their time is spent writing code.
