# vizTtianicSurvivors


####Sources:

#####Help with general JavaScript functions
http://www.w3schools.com/js/

#####Help with d3.nest()
http://bl.ocks.org/phoebebright/raw/3176159/

#####Help with d3 Bar Charts
http://www.d3noob.org/2014/02/making-bar-chart-in-d3js.html

#####Color Picker
http://colorbrewer2.org/

#####Positive/Negative Stacked Bar Chart Example
http://tributary.io/inlet/6116099

#####Help with Axes Labels
http://www.d3noob.org/2012/12/adding-axis-labels-to-d3js-graph.html


####Feedback:

######"I don't find the colors for male and female to be complementary."
After some back and forth, we settled on colors that were more pleasing to the eye: #b3cde3 for males and Accent Pink (#fbb4ae) for females.

######"It is unclear if the chart is showing number of survivors or percent of survivors.  Change the title or axis labels to reflect something like 'Number of Survivors/Number of Casualties"
Updated Chart title and y-axis label to be more clear.

######"It might also be cool to see the effects across age ranges of other factors, such as passenger class or embarcation location."
Added functionality to switch color sorting to allow audience to compare survival/casualty distributions for Sex, Passenger Class, and Embarkation location.

######"For the color of the graph, I would suggest using complementatry colors i.e. orange and blue."
As mentioned previous, updated colors to a more complementary color palatte.  Extended complementary color selection to additional sorting options.

######"Increase the font size of the axis labels."
After some clarification, we determined that the yAxis labels were too small and were getting blurred due to the effect of the rotation.  So I boosted the font size of the yAxis labels to 14px from 12px.

######"Provide better commenting for the functions, including any parameters needed and the expected result."
Went through and thoroughly commented the codebase for better readibility.



