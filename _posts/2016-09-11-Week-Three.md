---
layout: post
title: Week 3
---

<h2>What did you do this past week?</h2>
I finished testing and cleaning up the code for the Collatz project. There was a huge hiccup where my Travis builds
were failing because it was unable to find the four test files that I had submitted to the public test repo. In 
trying to fix it, I ended up breaking my private repo too. The master and dev branches were all over the place and
all sorts of issues popped up when I tried to merge them together. I was able to fix everything after a few 
frustrating hours. The root of the problem was including collatz-tests/ folder as a submodule in my private repo.
After removing it with "git rm --cached collatz-tests", everything was back to normal and Travis was able to 
successfully build my project. I'm definitely going to spend more time establishing a solid repository for the next
project to avoid having to deal with this headache again.
<h2>What's in your way?</h2>
I have a lot of reading to get through for all of my classes. After awhile they all start to become really bland and
I start glimpsing at the pages instead of trying to absorb the materials. I'm also aiming to get through Project 2 
for OOP as quickly as I can because the week after is going to be hectic with career fairs and all. 
<h2>What will you do next week?</h2>
I'm probably locking myself in the GDC to plow through Project 2 and another project for Networks while agonizing
over the fact that I won't be able to see Yeezus at the Frank Erwin Center.
<h2>Tip of the Week</h2>
I have a love hate relationship with git. It's a wonderful tool when used correctly and an incredibly pain when things
go wrong. I've been working with a GUI application for git called GitUp. It's an excellent tool for managing and
visualizing your repositories and their branches. It's only available for Mac but there are other equally high quality
applications for other OS. Check them all out here: [Git Clients](https://git-scm.com/download/gui/linux)
