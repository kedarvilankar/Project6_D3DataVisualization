# Project6_D3DataVisualization

#Summary
This visualization shows the probability of survival on Titanic by age, gender, and passenger class. The visualization also shows the relative number of passengers by the size of the circles in each age group of each class. The visualization indicates  following three things:
1)	The chances of survival of a female passenger were much higher than a male passenger.
2)	 The chances of survival of a passenger of Class 1 was higher than the passenger from other two classes.
3)	And, children in the age group of 10-20 had better chances of survival than the passengers from any other age group.

#Design
I used scatter plot to show the probability of survival on Titanic. The X-axis represents the different age groups of the passenger, and the Y-axis represent the probability of survival. The scatter points are plotted using circles, where the size of the circle represents the number of passengers in an age group or a passenger class. 
First, the visualization goes through an animation where the first visualization shows the probability of survival in different age group irrespective of the passenger class. Then animation continues to give a preview of survival rate in each passenger class. 
After the animation is over, four clickable buttons are added to the page for user interaction. The buttons enable the user to visualize and compare the survival in any of the passenger class.

#Feedback
I posted my first draft of the visualization on the forums for the feedback. Following is the link to the forum: 
https://discussions.udacity.com/t/feedback-on-the-visualization-made-for-the-project/219566?u=kedarpv
I received two feedbacks on the forum and one feedback from a friend, they are as follows:
Feedback 1:
•	I don't know what the size of the bubble means
•	The center of the bubbles seems a bit off from the axes
•	Style the axes a bit so they are less visually prominent
Feedback 2:
Using D3 is very hard. Dimple.js is much easier.
I suggest:
•	I think it is no need to using animation. Because there is no sequence between every chart.
•	Adjusting position of chart, let it in the middle of the browser.
•	Adding a "little hand" when you click the button. I got the opinion from peter_58389999326509:
"I also think its nice to make possible interactions obvious to the viewer: you can apply styles such as "cursor:pointer" to your clickable divs so the cursor changes when users hover over these elements"
•	The size of circle I think is number of people, explain it in your chart.
hope it help.

Feedback 3 (from a friend):
•	Add grid lines to x-axis for users to easily associate a circle to the corresponding age group.

Based on the feedbacks I made the changes to the visualization, however I did not remove the animation as one of the feedback suggested. I wanted to keep the animation because I feel it gives a preview of all the possible plots a user can see and then the user is free to interact with any of the plots. The following is the link to the gist of the new visualization. 
http://bl.ocks.org/kedarvilankar/6bbad92cf8799f1053704428ff420700


