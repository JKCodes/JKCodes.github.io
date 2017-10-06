---
layout: post
title:      "Projects and readme's"
date:       2017-10-06 00:32:48 +0000
permalink:  projects_and_readmes
---


Often times, I overlook the importance of the readme file.  Today, I finally learned one of the reasons why having a great readme file is something I should never neglect.  I heard from another programmer that my project always fails upon running 'npm start'.  Of course, the first thing I did to debug this issue was to run that very command on my computer, and for some reason, 'npm start' would never fail to produce any errors.  So, I just naturally assumed that maybe that person had forgotten to run 'npm install' first.  Then one day, I decided to see what would happen if I also cloned my project onto a different directory.  And soon after that, I found out the cause of the issue above.  This '.env' line on the .gitignore file was creating the issue.  This file is not included in the repo, and when I clone the project's repo, .env file was non-existent on my directory.  Had I written a comprehensive installation instruction, this issue could have been avoided!  Better write a readme file early and frequently now on, right?
