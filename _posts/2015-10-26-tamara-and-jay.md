---
layout: post
title:  "Tamara and Jay Report"
date:   2015-10-26 20:37:47 -0500
categories: jekyll update
tags: tamara_and_jay
---

From Jay: October 26, 2015

Tamara and I met from 6:30pm to 9:30pm on Tuesday 10/20. We went over what she had completed on her last CS50 assignment that she had submitted since our last meeting. She seemed really comfortable with most of the concepts. The concepts were mostly the same between her Ruby Asteroids game project and this C Breakout game assignment. The Breakout game was simpler and more low level.  We started going over her latest assignment. It's a very open ended and technical one based one the .BMP file format. I was able to help clarify some confusing points for her, such how byte order can come into play when trying to understand what's going on when reading the file and using the provided C struct from the class to read the BMP’s magic number, ASCII “BM”,  at the beginning of a file. The classes’ implementation however, used a 16bit short to read this in. She used gdb to get the value of the short integer, then she converted it to hexadecimal and looked up the ASCII characters. This made the value appear to be “MB” due to being on a little endian platform for interpreting the short. I convinced her to temporarily switch the struct's short to a char array of size 2, just to demonstrate that it really was “BM” on disk. The machine problem she is working on is actually difficult for me too. It involves color theory, which I'm not familiar with and isn't explained in her course material. I found an article that describes a formula that I think may work and sent it to Tamara. She's been out of town, so she hasn't gotten to try it out yet. We are not meeting this week.