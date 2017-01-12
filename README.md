# Data Visualization Project
# Udacity Data Analyst Nanodegree
## By Stephen Fox
## January 2017


## Summary

The purpose of my data visualization is to demonstrate the rapid growth in employment by Amazon over the last 15 years, and how that growth has been fueled by sales growth and major new product launches. Given the huge number of job openings in my town (Seattle) listed by Amazon, I wanted to further understand how their employment numbers have changed over time and also to put these numbers into the context of how much revenue the company is generating and also when new products were launched. To do so, I have constructed a timeline that demonstrates that employment growth has in fact lagged sales growth (i.e. outstanding sales appear to be driving the huge need for new employees) and have also overlaid the timeline with a few select key product launches (Prime, AWS, Kindle, Studio and Echo).


## Design

I decided that 2000 - 2015 would be an interesting period to cover, given that it covers all of the 21st century and provides a relatively long time frame while also ensuring the final graphic would not be too crowded. Since Amazon became a publicly traded in 1997, data from 2000 onwards was relatively easy to obtain from the company’s public filings with the Securities and Exchange Commission (SEC). Given that this is a time series of data, I opted to use line graphs for my initial design. I also decided to use two y-axes, allowing me to simultaneously show employment and sales figures. 

### Hand Sketch

The initial design sketch was as follows:

![Hand Sketch](https://github.com/sfox1975/Udacity-DAND-Project-6/blob/master/Hand_Sketch.JPG)

The sketch consists of two lines, one for sales and one for employment. 

### Coded Sketch - Take 1

Next, the hand sketch was transformed into code (see index1.html) and the results were as follows:

![Take 1](https://github.com/sfox1975/Udacity-DAND-Project-6/blob/master/Take1.png)

(Also available at: http://bl.ocks.org/sfox1975/raw/c6359b31c68f44a2636dde1637a60623/)

The chart was developed by using a line plot and a scatter plot for each data set, with sales in black and employees in green. The decision was made to use both a line and a scatter for enhancing the ability to see individual data points (via the scatter) while also seeing the trend over time (via the line). Once this plot was completed, it was distributed to a friend, a family member and posted on the Udacity forum, in order to get feedback.

### Coded Sketch - Take 2

Following self-reflection and feedback comments (see Feedback section for details), the following design changes were made:

1. Use a bar chart for one of the data sets in order to enhance the contrast.
2. Eliminate the use of color, since it serves no obvious purpose once the bar chart is used as contrast.
3. Add a subheading to provide additional context and explanation of what the audience is looking at in the graphic.
4. Enlarge and equalize the font sizes for the axes, for enhanced readability.
5. Use a modern, consistent font for all text (sans-serif was selected).

The resulting chart was as follows (see index2.html for the code):

![Take 2](https://github.com/sfox1975/Udacity-DAND-Project-6/blob/master/Take2.png)

(Also available at: http://bl.ocks.org/sfox1975/raw/03bde768e66dd178a729bc9d43926c2f/)

### Coded Sketch - Take 3

The Take 2 coded sketch was only subject to internal review, since it represented more of a halfway version of what I had hoped to achieve, but was worth a review since it was my first chance to see the bar chart / line chart combination. Based on what I saw, I decided to make the following changes:

1. Make employee count the primary data series (i.e. on the left y-axis), since the story I am conveying is focused on employee count growth.
2. Make employee count the data series that uses the bar chart, since I felt it better conveyed the idea that employment growth lagged sales growth (i.e. if this change were made, the bars would be below the line for most of the graph).
3. Add key corporate events to the graph via the addition of single point bubbles on the top of the chart.

The resulting chart was as follows (see index3.html for the code):

![Take 3](https://github.com/sfox1975/Udacity-DAND-Project-6/blob/master/Take3.png)

(Also available at: http://bl.ocks.org/sfox1975/raw/a4f2372c7d76916378ea3f5ec05dd83f/)

Once this plot was completed, it was distributed to the previous reviewers and posted on the Udacity forum, in order to get feedback.

### Coded Sketch - Final Version

The reviewers found the new iteration of the graphic to be an improvement compared to the original. The only feedback I received that required a coding change was the desire of one reviewer to see the ‘Corporate Events’ labeled in the chart legend. This change was the final change made to the graphic prior to submitting the project for review. The final code is available in index.html and the chart can be seen in the following screenshot and URL:

![Final Graphic](https://github.com/sfox1975/Udacity-DAND-Project-6/blob/master/Final.png)

(Also available at http://bl.ocks.org/sfox1975/raw/dec70ed20801b050f5efccc0aa1f2893/)

## Feedback

A key part of the iterative process of developing this graphic was to obtain outside feedback. For this project, I obtained feedback from three people. In each case, the person reviewed and commented on the Take 1 and Take 3 versions of the graphic. Their feedback shaped the changes I made at each step of the design process.

### Friend 1 Feedback

#### Friend 1 provided the following feedback after reviewing Take 1:

“The visualization is very clean and easy to understand. It shows the exponential growth of the company from 2000 to about 2015 measured in the number of employees and sales revenues.  The last 5 years has especially been great for Amazon.  Its growth at this time is spectacular and it appears to be continuing the upward trend in sales.  Its hirings has tracked the sales numbers with the greatest hiring rate increase occurring in the most recent year shown in the graph. The main takeaway appears to be the direct correlation between these two data (employees and sales) and the graph clearly shows how they track over time.

I recommend you try plotting one of the data sets with bars. It will be easier to tell them apart. I think you should make the fonts on the x- and y-axis bigger (they are hard to read).”

#### Friend 1 then provided the following feedbackk after reviewing Take 3:

“This is a much better graph.  Instead of merely describing a correlation between two data (number of employees and annual sales), it suggests or states a causation, i.e. that the sales drives the employment.  By adding milestones, it also explains the source(s) of growth.  Amazon has grown at such a fast rate and has expanded its offerings to include just about everything under the sun, and the graph is pretty well designed in showing how the company grew after the introduction of a particular product/service.”


### Friend 2 Feedback

#### Friend 2 provided the following feedback after reviewing Take 1:

“I like this graph, it is informative. I noticed that Amazon’s sales and head count have grown like crazy since 2000 and that they seem to grow in lock step, with employment lagging a little bit behind sales. Maybe you can point out some ‘famous’ Amazon events on the graph, since they started out just selling books and now do a lot more (AWS, movies, devices etc.). This is minor, but I would use a better font for the header and also change the wording to make it more impactful (‘Employment & Sales’ isn’t very descriptive).” 

#### Friend 2 provided the following feedback after reviewing Take 3:

“Looks nice! All I’d say is that I figured out what the orange dots do but maybe you should add them to the legend so that its obvious to the user.”


### Udacity Forum Feedback

#### User emmanuelle_185407894 provided the following feedback after reviewing Take 1:

“Very nice visualization, we do see that employment picked up a little later than sales. 
I like the simple and efficient way of your chart. 
We don't know really why the employment pick up later but I like how you relate to the information.

My only suggested change would be the employees y-axis on the right. 
I would put it on the left next to the sale, in different color and maybe with less ticks. 
The horizontal lignes are misleading, to my point of view, because we try to make a connection between the left y -axis and the right y-axis.”

#### User emmanuelle_185407894 provided the following feedback after reviewing Take 3:

“And you new graph is very good.”


## Resources

Github support for writing a .md file:

https://guides.github.com/features/mastering-markdown/

Numerous coding questions addressed via:

Stack overflow.com
(special thanks to John Kiernander, whose dimple.js knowledge is truly impressive!)

Key events in Amazon history:

http://www.telegraph.co.uk/technology/amazon/11801515/Amazon-timeline-from-internet-bookshop-to-the-worlds-biggest-online-retailer.html
https://en.wikipedia.org/wiki/Timeline_of_Amazon.com

The idea to focus on Amazon employee growth was inspired by the elegant ‘Quadrant I’ figure (Apple employment) available at:

http://dataremixed.com/2012/05/clarity-or-aesthetics-part-2-a-tale-of-four-quadrants/