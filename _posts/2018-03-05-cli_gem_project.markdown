---
layout: post
title:      "CLI Gem Project"
date:       2018-03-06 02:19:50 +0000
permalink:  cli_gem_project
---


No step-by-step instructions, no rpsec tests, no automated git pushes...no problem. Well staring at a blank screen is always a little scary, and sure, there was still plenty of Googling to be done. After one last video on getting started and planning your gem, everything started falling into place though. I found Avi's advice to start small and simple and slowly work your way up to a complete program, very helpful. Can you run your program and get "Hello World"? OK, now hard code some data in. Working one step at a time. Break your code, then fix it. Make decisions, and keep coding to find out if you are on the right path.

For my project, I chose to list some upcoming video games, then allow the user to choose a game to get a description of it. Video games take up a lot of my free time when I'm not learning to code. First, I got the program to run, and print "Hello World". Then I printed some hard coded data that I wanted to be able to see after the program was done. Then I got the user's input, and added simple logic to decide what happened next. Printing some more hard coded info for a game description, re-listing the games, and exiting with a goodbye message. Then came the code to create Game objects. Changing the original hard coded information to using data hard coded into the objects. After that, creating objects using information obtained from scrapers. The list display was adjusted to only show the first 10 games, instead of a super long list. Logic was then added to also show the next 10 games. The final step was to ask the user for a gaming platform, and tell the scraper to pull a list for the right platform. The user input logic was updated again to allow choosing a new platform.

Running the finished CLI app felt really satisfying. Seeing it pull different kinds of data based off the input I was giving it, was really cool. I struggled some at the beginning getting GitHub figured out, and remembering to do constant commits. Overall, I felt like the lessons leading up to this project really prepared me for the challenge.
