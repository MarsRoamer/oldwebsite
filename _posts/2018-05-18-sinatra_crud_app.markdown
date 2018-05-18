---
layout: post
title:      "Sinatra CRUD app"
date:       2018-05-18 16:37:50 +0000
permalink:  sinatra_crud_app
---


Just finished up with the Sinatra section, which was capped off with the completion of a CRUD app.  For my particular application I chose to create a user-sourced database of 'off the grid' hotspring locations.  What I enjoyed about it is that it was a culmination of everything we've learned from the course so far.  It is built using an MVC (Model View Controller) design pattern, and incorporates ORM (Object Relational Mapping) via Active Record. The build went relatively smoothly, and I really enjoyed building the functional component, but I did struggle a little in incorporating much of a front end.  Design is something that I've aways had a bit of a hard time with, I do much better if I have a mockup that I can refer to.  So the next application I build I will be sure to get something sketched up beforehand that can guide me when building out the front end.

I did have one particular issue that set me back a handful of hours, which happened to be when i was trying to style the site.  I was having a lot of trouble getting the stylesheets to refresh real time in the browser as I was building it, which led me to initially believe that it was an issue with how I was linking the stylesheets.  I could update the HTML and the changes would be reflected as soon as I refreshed the page, but if I tried to make any changes to the .css file,  they wouldn't update.  Then as I would be making small changes to the wording on my site, the stylistic changes that I made, sometimes hours ago, would appear!  Then I wondered if it was somehow Chrome would cache things, so I switched to incognito mode, and sure enough, any changes that I made to the stylesheets would be reflected upon refreshing of the screen. 

Upon a little further research, most modern browsers cache front end resources for performance reasons.  There are a couple of work arounds, one being what worked for me, and that was just using incognito mode.  A couple of other solutions are to do a hard refresh, which you open the dev tools, then right click on the refresh button, and select 'empty cache and hard reload'. Another suggestion I saw was to append the .css file with a random query string that way Chrome recognizes it as a new file each time, and therefor reloads it.  

The take away from all this for me was a reminder that when I encounter something that I can't seem to figure out, and is seemingly random, is to step back and look at the other possible causes.  I just assumed it was something that I was doing wrong, but rather it was a quirk with Chrome, and had I just researched some other possible causes, I probably would have saved myself a bit of headache and time.  Regardless, it's all part of the learning process, and that process never stops!




