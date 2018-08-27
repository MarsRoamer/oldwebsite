---
layout: post
title:      "Workout Tracker with JS"
date:       2018-08-27 17:56:56 +0000
permalink:  workout_tracker_with_js
---


For this project I refactored the user and gym landing pages.  I added add the option to cycle through and complete the previous workouts without refreshing the page.  For the gym landing page, I added the option to view all of the previous workouts that the gym has posted.  These workouts can be displayed and hidden without a page refresh.  There is also the option to comment on the current workout of the day.  These comments are added dynamically to the DOM so that they are displayed without a page refresh.  They are also added to the database so that the comments persist.  For the comments I used the AJAX response to create a JS object.  One of the methods that can be enacted on these objects is the ability to format the comment.  It takes the name of the commenter, as well as the content of the comment to display a uniform response.  


