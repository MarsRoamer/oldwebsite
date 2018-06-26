---
layout: post
title:      "Rails Portfolio Project"
date:       2018-06-26 03:42:18 +0000
permalink:  rails_portfolio_project
---


For my rails project, I built a workout tracking app for Crossfit gyms.  This app allows gym owners to post their workouts, and it allows the members of the gym to log their workouts.  Aside from getting my associations working properly, the build out went relatively smooth.  As far as my setting up the ActiveRecord associations, I had some difficulty with the has_many_through association.  This was mostly due to the fact that I didn't have a good outline when I started, but after poring  over the rails guide and taking the time to diagram everything out, it became a lot more clear.  

Another minor sticking point that I encountered was trying to implement omniauth for Google.  I setup this funcitonality after I had already completed the majority of the project, and had to account for some inflexibility in my associations. In my user model, I required the member/user to select a gym when they register, which was a bit tricky to incorporate using omniauth.  My work around was to create a gym to serve as a placeholder, and automatically assign the oauth user that particular gym.  When the user was then redirected to their show page, I added a conditional statement that triggered if the user's gym matched the placeholder gym, to which the user was then directed to the edit page to select their appropriate gym.  

Ultimately, this project really helped to solidify my undertanding of the fundamentals of rails.  I'm really looking forward to diving into javascript  so I can incorporate some more front end functionality.  If you'd like to check out the app, please go to https://github.com/MarsRoamer/Workout_Tracker.  



