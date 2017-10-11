---
layout: post
title:      "React, Redux, and file structure"
date:       2017-10-11 20:40:49 +0000
permalink:  react_redux_and_file_structure
---


Another thing I found while programming is that there is such thing as an efficient file/folder structure.   While this may be more of a preference for many developer, but for me, my previous file/folder structure made it very difficult to keep track of where all the files are located.  React/Redux apps have many imports on container files.  I found that because I had hidden away so many reducer files (as in, it was way too deeply nested in folders), it was becoming increasingly tedious and difficult to import these files as the project became more and more complex.  So for my next project, I should always remember that sometimes, simplicity is the right answer.
