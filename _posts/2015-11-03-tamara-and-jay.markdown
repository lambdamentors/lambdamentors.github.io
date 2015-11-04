---
layout: post
title:  "Tamara and Jay"
date:   2015-10-27 20:37:47 -0500
categories: jekyll update
---

====

From Jay: October 26, 2015

Tamara and I met from 6:30pm to 9:30pm on Tuesday 10/20. We went over what she had completed on her last CS50 assignment that she had submitted since our last meeting. She seemed really comfortable with most of the concepts. The concepts were mostly the same between her Ruby Asteroids game project and this C Breakout game assignment. The Breakout game was simpler and more low level.  We started going over her latest assignment. It's a very open ended and technical one based one the .BMP file format. I was able to help clarify some confusing points for her, such how byte order can come into play when trying to understand what's going on when reading the file and using the provided C struct from the class to read the BMP’s magic number, ASCII “BM”,  at the beginning of a file. The classes’ implementation however, used a 16bit short to read this in. She used gdb to get the value of the short integer, then she converted it to hexadecimal and looked up the ASCII characters. This made the value appear to be “MB” due to being on a little endian platform for interpreting the short. I convinced her to temporarily switch the struct's short to a char array of size 2, just to demonstrate that it really was “BM” on disk. The machine problem she is working on is actually difficult for me too. It involves color theory, which I'm not familiar with and isn't explained in her course material. I found an article that describes a formula that I think may work and sent it to Tamara. She's been out of town, so she hasn't gotten to try it out yet. We are not meeting this week.

====

From Jay: October 12, 2015

Our last meeting was Tuesday September 29th, 6:40 - 9:10pm.  It was our first session since her Ruby project was finished and she needed to get back into the swing of things in C. We went over all her original first 2 weeks of machine problems from the CS50x class. Now having a fresh look at them, with everything she learned from the Ruby project, I had her refactor them. It went really well. Our next meeting was supposed to be last week Tuesday, but she had the flu. We’ve rescheduled to meet tomorrow.

====

From Jay: September 2, 2015

Tamara and I met Monday, August 24th. We went through almost everything left on her portion of the Asteroids project that was needed to make it a playable game. She mainly worked on making the laser until she was happy with the visuals and behavior of them. She also refactored the shared drawing code to take an optional transparency parameter, so she could draw a motion blur for the laser spinning.  When her group met later that week, she was able to help other people with their tasks, mainly the asteroids weren't using the physics and collision detection yet.  The game is pretty playable now and ready for a demo at Lambda Lounge.

========

From Jay: August 24, 2015

We still continued on the Coder Girl Cohort Project. It's almost done.

Met with Tamara from 7-9pm August 12 at Coder Girl.

Helped guide her through the following issues

[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/12](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/12)

[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/11](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/11)

[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/10](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/10)

That went relatively quickly and then she finally added UFO collisions.
[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/5](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/5)

Met with Tamara from  6-9:20pm August 19th at Coder Girl.

We mainly worked on lasers in the game. She had a pretty good start because she started working on it from what I originally spec'd out:

[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/17](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/17)

Also, a couple days before our meeting, she emailed to ask about Git branching, because she wanted to continue working from a different part of the history, before some other group member changes, to make it easier to test the lasers. When we met, I encouraged her to refactor a bit of the code she wrote for the player so that she could reuse much of what she built for the ship.

Although lasers weren't completely finished, we stopped at a good point. Now she's reached a fun part of the project because all the infrastructure is there and there's a lot to just play with to get it to look just right.

====

From Jay: August 6, 2015

We met 7/30 from 6:10pm-9:20pm. We continued focusing on the group project.  Tamara worked on using the collision handling functions in the physics engine to determine if the ship is touching the edge of the screen and then draw its overlap on the opposite side. This was a task I came up with the week prior as a way to learn how the collision handling works and also build on what we've already done.

[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/8](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/8)

After it was done, it became obvious that the original geometry code had some edge cases the kept it from looking smooth, so the result was pretty cool.

Afterwards, I wrote some new issues for things she could use to learn or improve upon based on some visual artifacts that she noticed.

[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/10](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/10)

[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/11](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/11)

[https://github.com/dummey/CS50-Cohort-Project-Redux/issues/12](https://github.com/dummey/CS50-Cohort-Project-Redux/issues/12)

====

From Jay: July 27, 2015

Last week Tamara and I met at the Coder Girl meeting from 6:10-9pm. We continued with the Cohort project Asteroids in Ruby. Our focus was integrating a physics engine, Chipmunk, into the existing code base by swapping out a bit of the basic geometry that was previously done by hand. By the end, she had a ship flying around with thrust. It was pretty cool. We do not have another meeting on the books yet.

====

From Jay: July 15, 2015

Met with Tamara last week 7/9 from 6:20pm to 9:25pm.  Our main focus was her group Cohort project in Ruby.  Although she's been doing the Codecademy Ruby tutorials, it hasn't yet gotten to Object Oriented Programming, but she's certainly become more fluent in Ruby. Her next task in the Cohort project was related to the player ship from their Asteroids game. We focused on event handling and worked on making the ship rotate using the arrow keys. This gave her the basic framework for how to handle key presses before doing more complicated things like thrust and firing. We are not meeting this week, but I also emailed her some follow up information that I found on handling physics using their Ruby game library. That is her next assigned task.

====

From Jay: June 25, 2015

Met with Tamara and also expected to meet with her Cohort project group at the weekly CoderGirl. However, she was the only one to show up. Her Cohort group project, due to people dropping, has switched to implementing the game Asteroids in Ruby with the Gosu game library. She implemented a moving star background for the game. This meeting lasted 6pm-8:20pm.

Crystal [tweeted a picture](https://twitter.com/LaunchCoderGirl/status/613867291244150784).

<blockquote class="twitter-tweet" lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/LambdaLounge">@LambdaLounge</a> mentor <a href="https://twitter.com/jbtule">@jbtule</a> hanging with CoderGirl Ther making an asteroids game! <a href="https://twitter.com/hashtag/YouCodeGirl?src=hash">#YouCodeGirl</a>! <a href="http://t.co/MHs4dtWCi5">pic.twitter.com/MHs4dtWCi5</a></p>&mdash; LaunchCoder Girl (@LaunchCoderGirl) <a href="https://twitter.com/LaunchCoderGirl/status/613867291244150784">June 25, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

====

From Jay: June 17, 2015

Tamara and I met up again at wifi cafe from 6:20pm to 9:15pm, Tuesday 6/16, with breaks, so I'd estimate 2.5 hours again. We mainly focused on her group project. She still has more to do in her Ruby tutorial, so we chose a simple task assigned to her and worked through it. This gave her the general idea of how to work on a task in Github. We started with versioning in Git, creating specs with Rspec, running the tests, implementing features piecemeal, and referencing issues with the commits.  A lot of time was spent getting Windows to work well with a decent workflow for Ruby, but we got it by the end. We are going to try and schedule meeting up again next week, but we don't have anything on the books yet.

====

From Jay: June 15, 2015

Tamara and I met at a wifi cafe from 6pm-9pm last week Tuesday June 9th. That meeting had breaks, so a safe estimate of 2.5 hours of mentoring.

We started out with her current MP in CS50, which has a very simple instruction: implement Breakout. But that instruction has a lot of leeway in what the final product could be.  We basically went over what she had implemented already, and I talked her through refactorings as related to how she wanted to customize her version of the Breakout game. I encouraged her to use the C std library functions more, since she was refraining. She worried that they made the implementation too simple. We also went through using the gdb, since this was her first gui assignment and printf's did not work.

The rest of our time was spent going over her CoderGirl group project in Ruby. She had been assigned some tasks in Github, but didn’t have any experience with Github, Git, or Ruby yet. We went over Git and Github, and finished getting her environment setup for working on the project. She has already started Codecademy Ruby tutorials, but she needs to spend more time on the tutorials before starting the tasks assigned to her. We are scheduled to meet again Tuesday, June 16th.

====

From Jay: May 28, 2015
The charity I’ve chosen is [Safe Connections](https://safeconnections.org) they are local and also a United Way partner.

Tamara and I corresponded through email this week and did not meet, but we did figure out places with wifi that were convenient for both of us to meet if not on a codergirl night.  We are planning on trying to meet next week, but my schedule is a bit variable next week specifically, so we don't have anything on the books yet.

