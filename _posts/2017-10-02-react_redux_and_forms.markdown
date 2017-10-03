---
layout: post
title:      "React, Redux, and Forms"
date:       2017-10-03 02:33:16 +0000
permalink:  react_redux_and_forms
---


Today, while I was testing my app, I found something interesting.  When I sign up for a user, then log out, and then go back to the sign up page, I found that all of my previous information (including the password!!!) was still filled out on the form.  I then quickly realized what was causing that; the reason was that I saved the form data on the redux state.  Since the data was semi-persisted because of redux, the previous form data was still saved even though the user had already left the sign up page!  This was a not a good thing.  This was one scenario where redux actually hurt more than helped.  There really was no reason for the form data to exist on the redux store.  
