# vizTtianicSurvivors


###Introduction and Notes:
For this visualization, I utilized the RMS Titanic survivors data from the Machine Learning 101 competition on Kaggle.com.  The effect I wanted to demonstrate in the graphic initially is the notion of 'Women and children first', made popular by such oceanic disasters back in the 1800s and 1900s.  The design of the graphic was also made to give the hint of an iceberg, as well, with a majority under the xAxis, and declining distributions towards the edges.  To accomplish these points, I utilized a Stacked Bar Chart with a position encoding to denote not only group passengers by their age range, but also to separate out those who survived (above the xAxis) and those who died (below the xAxis).  Furthermore, I utilized color to distinguish between the female and the male passengers to give a representation of the count for each group within the age ranges.

One point of note for this dataset is that it did come from a Machine Learning competition data files as a Training Set.  This means that the data backing this visualization is not a complete recount of the passengers of the RMS Titanic.  The remainder of the passenger data, however, has had the information regarding the passengers' survival striped to make the competition a challenge.  However, even with this subset of the passenger list, one can easily make out the general distributions across the filters.

###Design
I chose to share my findings using a stacked bar chart to represent a compact visual comparison Survivors vs Casualties across age groups with the avaiability to include Sex, Passenger Class, and Embarkation Location.  I think the stacked bar chart, with positive and negative values, offers a great visual experience when viewing this visualization by allowing the audience to easily distinguish the distribution of survivors and casualties and allows for further distinction by other factors.  In addition, it lends itself nicely to taking on an almost iceberg-like appearence, with trailing ends and a larger group under the xAxis than above.

The age groups were separated by position along the xAxis in distinct bars within the stacked bar chart, ordered from the youngest group to the oldest group.  Position was also used to encode the Survivors and Casualties, survivors sitting above the xAxis and casualties sitting below.

Color was utilized to further break down the age groups by Sex.  This was chosen to take advantage of the natural distinction of male and female with blue and pink hues, respectively.  In addition to this, I provided the ability for the audience to explore the data a little further by utilizing color to separate the passengers based on Passenger Class and Embarkation Location as an alternative to their Sex.  The colors utilized for the Passenger Class and Embarkation Location were chosen to be complementary to the colors of the Sex, to not distract from the data.  To do this, I utilized ColorBrewer2 to pick a color set to utilize within my graphic.

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

######"Chart not Explanatory"
Updated chart title to reflect the story I'm attempting to share with the audience.  In addition, I added some text to the graphic detailing the history of the saying 'Women and Children First' and inviting the audience to exlore the data further.

###Revisions:

######Revision for Review 1
http://bl.ocks.org/gregnutt/f5fd434e9970009d456e

######Revision for Review 2
http://bl.ocks.org/gregnutt/6eb5a1bd68f60b702892

######Revision for Review 3
http://bl.ocks.org/gregnutt/d42f7317092fc1fa910f

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


