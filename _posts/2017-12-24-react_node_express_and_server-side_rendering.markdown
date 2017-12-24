---
layout: post
title:      "React, Node Express, and Server-Side Rendering"
date:       2017-12-24 22:59:25 +0000
permalink:  react_node_express_and_server-side_rendering
---

One thing I realized while working with node server is that often time the page won't load once the page was reloaded.  One way to fix that method was to use server side rendering.  This allowed the server to load the react code server side and send it over once a route is matched.  One other benefit of server side rendering is that the current user reducer data can be sent over to the react side.  This meant that the page does not need to flicker because the react has to wait for current user data.  This made the page more fluid and crisp. 
