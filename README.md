# vizTtianicSurvivors


###Introduction and Notes:
For this visualization, I utilized the RMS Titanic survivors data from the Machine Learning 101 competition on Kaggle.com.  The effect I wanted to demonstrate in the graphic initially is the notion of 'Women and children first', made popular by such oceanic disasters back in the 1800s and 1900s.  The design of the graphic was also made to give the hint of an iceberg, as well, with a majority under the xAxis, and declining distributions towards the edges.  To accomplish these points, I utilized a Stacked Bar Chart with a position encoding to denote not only group passengers by their age range, but also to separate out those who survived (above the xAxis) and those who died (below the xAxis).  Furthermore, I utilized color to distinguish between the female and the male passengers to give a representation of the count for each group within the age ranges.

One point of note for this dataset is that it did come from a Machine Learning competition data files as a Training Set.  This means that the data backing this visualization is not a complete recount of the passengers of the RMS Titanic.  The remainder of the passenger data, however, has had the information regarding the passengers' survival striped to make the competition a challenge.  However, even with this subset of the passenger list, one can easily make out the general distributions across the filters.

###Feedback:

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

###Sources:

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


