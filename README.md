# README

This is a Pinterest-clone following the tutorial by [Mackenzie Child](https://mackenziechild.me/) in his
[12-apps-in-12-weeks](https://mackenziechild.me/12-in-12/) series.  
* The video for the tutorial is located here: [Week 8: How To Build A Workout Log In Rails 4](https://mackenziechild.me/12-in-12/8/) and here: [Youtube](https://www.youtube.com/watch?v=2_Lbj3slZUY&index=8&list=PL23ZvcdS3XPLNdRYB_QyomQsShx59tpc-)
* Mackenzie's GitHub repo for this project is here: [workout_log](https://github.com/mackenziechild/workout_log)


####Things to look up later
* [UI Gradients](http://uigradients.com/#)
* [CSS3 Generator](http://css3generator.com/)
* Is there a good color palette picker out there?

#### CM Comments
* in HAML, the "-" is like "<%" which just evaluates the Ruby while "=" ~> "<%=" which outputs the Ruby
* When creating the exercise partial, we originally named it "_exercises.html.haml" and despite referencing 
"= render @workout.exercises" in the workouts/show.html.haml file, the app couldn't find it.  We changed the name
to 'exercise' singular and that fixed problem
