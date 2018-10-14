# Explanatory Data Visualization Using D3 and dimple.js

## Summary

This dataset contains 1,157 baseball players including their **data**:

handedness (right or left handed or both), height (in inches), weight (in pounds),
and their **performence**:

batting average, and home runs.

After analysing the data,  I decided to make two visualization. First analyze the data for performance „batting avarage“ of baseball players based on their Height. Second, analyze the performance „batting average, and home runs“ based on their handedness.

## Design
I‘ll create a visualization that can help the reader understand the relationships, I used simple elements and colors to avoid confusion. An informative visualization can be simple and give message to the reader.

Since I know which visualization I will provide it is time think about what kind of plots will be used. For the first plot I decided to make a line plot, for the second a bar plot.

In plot 1, I first drew a 2 dimension plot, displaying height and batting average. I grouped the data by height and I could immediately see a negative correlation between these two variables. As the height of players increased, their batting average (BA) intended to drop. The best way to show this correlation was to use a line plot, and adding points for each height group. If the mouse hovers over points on lines, height and batting average will be shown. 

In my second plot, I decided to observe how handedness is related to the batting average and home runs. The best graph would be bar graph. I also add a line plot to this graph for batting average related to handedness. According to this graph left handed players makes more home runs then right handed and both. In batting average left handed and both handed players tend to make higer batting average.





## Feedback

### Feedbacks

I shared the initial visualization with my collegues and feedback to me was to position the title in the middle. 
Another feedback was to add short explanation to the graph and data. It is then easier to anderstand and follow the graph.


## Resources
- https://blog.decayingcode.com/post/Easy-Charting-in-JavaScript-with-d3js-and-Dimple-from-CSV-data/
- https://gist.github.com/rgilredondo/4580cf3269e5461efb866d47a6e94c4c
- https://www.sitepoint.com/create-data-visualizations-javascript-dimple-d3/
- https://bost.ocks.org/mike/bar/
- https://stackoverflow.com/questions/33179439/d3-js-dimple-getting-a-title-on-a-graph
- http://dimplejs.org/
