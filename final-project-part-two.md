[Home]( https://pbm15.github.io/Mitchell-Portfolio/)

# Wireframes / storyboards
https://carnegiemellon.shorthandstories.com/a-storm-is-brewing-the-climate-crisis/index.html

# User research 


## Target audience
For this "article," the target audience consisted of two groups. The first group is people who are interested in climate change and want to learn more about it and the impacts it has on our lives. The second group is professionals in environmental conservation who might be interested in finding unique data visuals to help them in their jobs.

## Interview script
1. What was your main takeaway from each graph? The goal of this question was to see if the viewer was able to see the main data/ story I was trying to highlight.

2. Did you see a story being told in the data? The goal of this question was to see if the viewer was able to connect the pieces of the story from visuals and put them together to see the larger picture.  

3. How could the graphs be made easier to read/ understand? The goal of this question was to identify any areas in the visuals that were confusing or were visually cluttered and how to address these issues.

4. Was anything confusing or in need of an explanation? The goal of this question was to find if there was any section of the "article" that was confusing in its layout or that could be adjusted to help better tell the story by aiding the visuals with more text explanations.

5. Did the theme of the webpage fit with the story being told? The goal of this question was to identify if the aesthetic theme matched with the story being told by the data.

## Interview findings
Question 1
  Int 1: Yes, but the use of color could be helpful to highlight the desired pieces more
  Int 2: Needs better titles to help explain the graphs
  Int 3: Footnotes to explain uncommon words
  
Question 2
  Int 1: Yes
  Int 2: Yes, but strengthen it with the writing before the visuals
  Int 3: Yes
  
Question 3
  Int 1: Highlight the lines of best fit, not the data line
  Int 2: Include a more detailed legend
  Int 3: Include a more detailed legend and expand the axis on the scrollable chart to make the data less cluttered
  
Question 4
  Int 1: No
  Int 2: Could add some data before the visuals to help create a clear idea of what the viewer should focus on in the visuals
  Int 3: some of the definitions around tropical storms and cyclones could be added
   
Question 5
  Int 1: Yes
  Int 2: Yes, make sure to use images of ocean and storms
  Int 3: Yes, visuals of the storms being tracked would also be helpful

# Identified changes for Part III
I plan to add much more detail to the written sections of the "article." in addition, I need to do some more research to find some data that will help tell my story, as well as research in the final call to action section. I also need to edit my graphics to be more visually appealing and to articulate the story I am trying to tell better visually. I also need to add a new ledged for the scrollable chart that is more thorough and several footnotes for the various charts explaining ideas or words that are not common knowledge.

# Methodology
To create this story, I have had to heavily edit and manipulate my data from NOAA to create the scrollable chart. Initially, I had thought that the pages feature in Tableau would be able to do everything I needed it to, but this was not the case. To get the data to work how I wanted to, I had first to sort the data and find a way to cull it to what I needed. To do this, I sorted the data by year, cyclone number for that year, and max wind speed. After this, I created a formula to calculate only the first entry for each cyclone. This reduced my data from ~50,000 rows to ~2,000. I then had to create a new date column that removed the year, to do this, I created a formula that subtracted the year from the date data, as they were both held as numbers, not dates. I added the same year to each date from this new column to create two different date columns. I then used the dates with the same years to form my axis and then the dates with the actual years to sort with the pages function.

