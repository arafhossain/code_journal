---
layout: post
title:  "Pleasant beginnings"
date:   2020-03-24 10:34:38 -0500
---

Ugh, what a day! Spent a lot of my day first getting this Jekyll blog setup on my Github pages, and then eventually succeeded in configuring my Amazon device to play the audio file I've been wanting to stream out of it using their developer console.

### Jekyll hosted on Gh Pages
Their documentation is a bit outdated and the youtube walkthroughs they referenced were also a couple of updates past, but thanks to random Youtube comments, I was able to diagnose and get my project up and running. Was mostly design choices taking time after the initial successful render. In particular, the site's footer settings. I had to recopy the '_includes' folder in a gem file into my repo and make an edit in the footer.html so it would override Jekyll's default theme. Thank goodness for frustrated people posting on Stack Overflow.

~~Set up blog~~

### Amazon Alexa Audio Stream
Setting up the Amazon stream was much more troublesome. Following a tutorial that was illustrating how to test a newly-developed skill on an Echo device, I couldn't understand why my device wasn't responding to my demo skill name. I rewatched the tutorial and satisfied I followed instructions to the letter began digging around the developer console, to find that the Amazon folks changed the initial configuration to give the skill a different invocation name than what previously was the skill name. After making that fix and finding out that my audio file had to be in a certain format, I signed up for a free for 12 months AWS account and uploaded my file there. After that, my Echo picked it up without issue! Hopefully I can find a free alternative before the free tier limit lapses.

~~Figure out how to make Alexa stream custom audio files~~