# Data-Viz
Repo for Data Visualization Project

## Summary:
My visualization explores Baseball player Homeruns vs their Height. The data set contains 1157 players and includes data on their
handedness(right,left, or both), height(in inches), weight(in pounds), batting average, and home runs. The chart attempts to convey the relationship between the number of Home Runs a player hits vs their height. The user is 
able to filter the players by their batting handedness to further explore this relationship. The relationship seems to follow a normal distribution with a median height of about 73 inches. 
When a user filters by handedness the following outcomes can be seen:

* Players between 71 - 76 inches appear to hit the most homeruns.
* There are more right handed batters than left and both handed batters.
* The player with the most home runs is left handed.
* Left handed players seem to hit more home runs on average when compared to right and both handed batters.




## Design:
After exploring the data, I decided to convey a relationship about a player's height and how many homeruns they hit. Because I wanted to
convey a relationship in the data, I chose to use a bubble chart. I chose to encode the player handedness as an additional variable to give the user the ability to filer by batting handedness and provide interactivity.
This encoding can be seen in the bubble color. 

Several Iterations have been made to incorporate feedback that was given. 

* Iteration 1 - Initial Sketch
    * Inital scatter plot created with Handedness encodings. 
  
* Iteration 2 - Responding to issue items 1-3
  * Chart Title and color Legend added to provide context for visual.
 
* Iteration 3 - Responding to to issue item 4
  * Added ability to filter chart on handedness to provide interactivity and animation. 
 
* Iteration 4 - Responding to issue items 5-9
  * X-axis information was not showing up well in Firefox. Added some styling to fix this issue. Added HR to y-axis to clarify what HR means in the data. 
    Improved the description and directions how to interact with the color legend. 
  


## Feedback:
  For anonymity purposes, I will use Reviewer # to document feedback I received from each individual who looked at my chart.  
  
  * Reviewer # 1:
	* Needs a general title to start you thinking about what the data is. On first starting it I can see height on one axis and HR on the other. 
	  I'm suspecting that HR may be Home Runs - so baseball but took me a little to get that far. 
	  I'm assuming now it's probably the # of homeruns for players based on their height, so possibly "Understanding how Major League Players height is related to the # of Home Runds they've Hit". 
	* The colors are interesting and would seem to indicate that there is some differentiation between players that could be seen in the colors but no legend appears so not clear if this is so. 
	  As I look further - clear it is Right, left and both handedness.
	* Because there is a lot of overlapping in the dots it leads me to wonder how big the population is (maybe 100 players or is it 1000s and in fact then what is the basis for the selection - 
	  is it all Major Leaguers or a subset or more than that league and for what timeframe.
	* I find myself wanting to see just the left handers and then just the right and switch back and forth to see the differences e.g. seems more right than left - but left have the highest totals, 
	  but in the middle with so much data, cant really see the differences.
  
  * Reviewer # 2:
	* The X-axis was not showing the information in Firefox.
	* What do you notice in the visualization? - There is information about the total of Home Runs and Height in inches per player.
	* I don’t understand what those colors mean. I don’t know what this “Click legend toshow/hide Battter Handedness” is. What is blue-R, Red-L, and Orange-B?
	* What do you think is the main takeaway from this visualization? - Players that are between 71 and 74 inches high and left-handed have the most home runs.
	* There should be between parenthesis (HR) after the word Home Runs, so we can know what those letters mean when putting the mouse on a player.
	
  * Reviewer # 3:
	* What do you notice in the Visualization?
	  The ambidextrous players were harder to tell apart due to the light color. When the other points overlay them, they disappear.

	* When the page first opened the legend was not visible in the page. After opening the page wider and using the legend to display or hide points, the legend was closer to the data. 
	  However, when the graph scales, the legend falls within the lines of the graph, making it harder to read. 
	  Maybe it could have a white background or something could be done to keep it out of the graph data (different location?).
	  I liked the scaling of the graph when items were selected or deselected and I liked the ability to select items within the graph.

	* What questions do you have about the data?
	  The color changes (darker and lighter) between the three categories of players, but it is hard to know what the meaning is for the changing colors.

	* What relationships do you notice?
	  The player with the most home run hits was left handed.

	* What do you think is the main takeaway from this visualization?
	  I saw a greater relationship between handedness and home runs than between height and home runs. I think the scatterplot is meant to convey something other than what I took away from it.

	* Is there something you don't understand in the graphic?
	  I do not understand the significance between handedness and home runs. The graph seems to be about height and home runs, and the additional variable makes me wonder what the relationship is between the three.
	  Additionally, it's hard to see the differences between dots. How many people were included in this study? Are they from one team or multiple teams? Why did you pick them?

	* People who have issues with color blindness may have difficulty telling the difference between the red dots and the other colors.
	
 * Reviewer # 4:
		* What do you notice in the visualization?
		  Not knowing anything about the data source, i’m assuming this is a scattergram of individual observations. 
		  The legend colors correspond to the handedness of the player, but it does not describe the shading. so, i interpret the color shading to be the density of occurrances at that coordinate.

		* What questions do you have about the data?
	      my main question about the data is why the height is represented as integer/discrete values, vs. real values. 
		  Home Runs make sense as integers. Is it to emphasize the clustering of occurrences? perhaps real values are too diffuse to project trends?

		* What relationships do you notice?
		  conclusions i would reach:
			* the distribution of height vs. home runs seems to fit a fairly normal distribution around a mean of 73.
			* leftys seem to have a higher percentage of the top home run hitters.
			* on average, rightys hit more home runs.				* obvioulsy significantly more rights than lefties.

		* What do you think is the main takeaway from this visualization?
		  demonstrate the effect of handedness and height on home run production.

		* Is there something you don’t understand in the graphic?
	      cool visualization.
	
	

## Resources:
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_storyboard_control
