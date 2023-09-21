# Visualizing Student Debt in the United States
Telling Stories with Data

Assignment 3 & 4: Critique by Design

Author: Clarissa Clifton

[Link to homepage](https://cjclifto.github.io/tswd_portfolio/)

## Original data visualization background
The visualization I chose to critique and redesign is about student debt in the United States. [The Forbes article in which I found the data](https://www.forbes.com/advisor/student-loans/average-student-loan-debt-statistics/)
appears to simply point out how much the cost of college-level education has increased, rather than pointing out any trends or making any analysis. It reads as a fact list with raw data included.

## Critique
First, let's take a look at an example data table in the Forbes article: 

<img width="742" alt="forbes_table" src="https://github.com/cjclifto/tswd_portfolio/assets/140766598/c1aa7f76-e6de-4be9-9a80-bd8da6b54f2b">

This table continues for all fifty states, and similar tables are recreated throughout the article summarizing a few other student debt metrics. Let's critique this data visualization technique using Stephen Few's Data Visualization Effectiveness Profile:

<div class="tableauPlaceholder" id="viz1695262870557" style="position: relative">
  <noscript>
    <a href="#">
      <img alt="Data Visualization Effectiveness ProfileForbes's Student Debt Article" src="https://public.tableau.com/static/images/st/studentdebt_ratings/Sheet1/1_rss.png" style="border: none" />
    </a>
  </noscript>
  <object class="tableauViz" style="display:none;">
    <param name="host_url" value="https://public.tableau.com/" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="studentdebt_ratings/Sheet1" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
    <param name="static_image" value="https://public.tableau.com/static/images/st/studentdebt_ratings/Sheet1/1.png" />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
    <param name="filter" value="publish=yes" />
  </object>
</div>
<script type="text/javascript">                    
  var divElement = document.getElementById('viz1695262870557');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

### Usefulness
The data is useful in that it outlines trends in student loan debt in the US. Forbes’s main audience is business owners and entrepreneurs - bc student loan debt generally decreases spending, it may be important for businesses to know where in the country they might see decreased spending from certain demographics. However, the way the data is presented, it’s just an information dump, and the link to decreased spending isn’t explicitly made.

### Completeness
All data points are present for multiple metrics, and a reader could make their own conclusions by noticing general trends if they worked for it. However, no trends or comparisons for contextualization are made by the authors, and too much data may be included; feels more like a supplemental info document than an article trying to argue a point.

### Perceptibility
All data is presented in table format. This is an easy to understand and generally familiar data format for readers, and data in this article is organized into categories/columns that make intuitive sense. 

### Truthfulness
Article references data source multiple times throughout, and clearly replicates data from source. Data source is from a federal institution, so should (theoretically) be the most reliable source for the given financial data. There isn’t much chance for misrepresentation, however, as the article basically copy/pastes the source data and makes a few formatting changes. 

### Intuitiveness
Tables are a generally familiar and easily understood data format.

### Aesthetics
The table is nicely organized and generally clear-looking, so it can’t be scored as 100% ugly. However, it is a massive wall of text to look at, which would overwhelm most viewers and doesn’t do much to aid in making any kind of point. It’s an information dump.

### Engagement
Again, the wall of text invites the reader to look for about 3 seconds to see if they can draw any intuitive conclusions themselves, but is just overwhelming/boring after that. The onus of making a point is placed not with the author of the article, but with the audience of that article - which is kind of backwards!

### Overall thoughts
The first thing that stood out to me with this data visualization was the missed opportunity(ies) to make a point to the audience. Comparing the article data to the source data, it appears that raw data from the source is itself being used as the data visualization to the target audience. I liked that the data was at least organized and formatted well, but not much else. I didn’t like that there were too many data points in the visualization without a trend being drawn; this could be improved by changing the visualization type used (even to something as simple as a bar chart) and decreasing the number of data points used (e.g., only the top and bottom 5 states are specifically called out). I didn’t like that the onus to draw a conclusion was placed on the reader, rather than controlled by the author, because it seemed like the article was more of a data report rather than taking a stance or making a call to action. Something I would do differently for this data is to create a different type of visualization that is more engaging for the audience and allows for trends to be easily seen. 

### Does this work for the primary audience?
The primary Forbes audience is young, entrepreneurial business owners, managers, professionals that are generally successful in their careers and ambitious to improve their businesses/careers. This visualization is not effective for reaching this audience for a number of reasons, but the main one is that there is too much information! Young professionals are generally an on-the-go demographic; they don’t have time to sit and read through lines of data points and make hypotheses, then scroll back through 40-50 other lines of data across multiple tables to corroborate their hypotheses.

### What would I change?
The data visualization effectiveness profile method is a good tool to evaluate the visualization I selected, because it covers aspects of a visualization that focus on the quality of the communicated information. For example, it doesn’t focus on the pure aesthetics of the visualization from an artistic stance, but rather on whether or not the aesthetics either improve or detract from the audience's understanding of the message. I don’t feel there is anything obvious missing from this evaluation method. For my chosen visualization, the first thing I would change is the visualization type. I plan to play around with a few different types to see which I like the best; at the very least, a bar chart would be a drastic improvement to the original tables. The second thing I would change is to combine the information presented across numerous tables in the article into one (max 2) graphics. The data is presented without much actual stance being communicated; integrating the information from multiple sides of the student debt crisis would allow the reader to have a holistic understanding of how pervasive the massive amount of student debt in the US is. A data visualization is a bit of a wasted effort if it’s not used to make a point about something.

## How can we make this better?
I think the original data vis can be made better in numerous different ways; first and foremost, let's actually *make* a visualization with the raw data! The first idea I had was to select only a subset of the tables presented in the Forbes article to focus on. I chose the debt by location and debt by loan type tables to focus on. For the debt by location, my idea was to make a hex map - the thought here was to avoid making the point of caution pointed out in my government debt assignment of making darker color/higher value regions on a map look less important because they take up less space on the map. With a hex map, I figure it will be easier to see states that stand out in value, not size. I also wanted to make some sort of animation across time with the debt by loan type data. I also thought of making a static line graph that represented the number of people granted each loan type per year with the size of the dot on each data point. Sketches of each are shown below:

![studentdebt_wireframe](https://github.com/cjclifto/tswd_portfolio/assets/140766598/02b76efa-faa0-486a-8398-6a0d05921589)

![studentdebt_idea2](https://github.com/cjclifto/tswd_portfolio/assets/140766598/eea7879b-14b9-4cd1-9be9-309c471f5e24)

## Critique... of my designs
I made some rough versions of my map and time animation, then spoke to two other people unfamiliar with my data to assess how my redesign ideas stood up. Main points from their responses are summarized below.

<div class="flourish-embed flourish-map" data-src="visualisation/15086180"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<div class="flourish-embed flourish-scatter" data-src="visualisation/15091594"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Student, late 20s
Hex map:

*What does this communicate to you?*

There is higher student debt in the Eastern United States, and not much in the Southwest.

*Is there anything confusing about this?*

Not much confusing with how the data is laid out, but a lighter color for the lesser values implies a loan value close to $0. The lowest value shown is actually $18k, so the amount is still high. Suggest changing the color scale to where the lowest value ($18k) is still obviously red, then the highest value ($40k) can be a much darker red.

Debt by Loan Type animation: 

*What does this communicate to you?*

Direct loan debt has increased over time, but the other two loan types have decreased over time. Why is that? There has been a drastic increase in student loans in the last 

*Is there anything confusing about this?*

The animation is cool, but difficult to understand at first glance. I have to watch the loop a few times to understand what is being communicated. An area plot might be a better way to visualize this data statically, if the message you're trying to get accross is the increasing level of debt overall.

### Adult, early 30s
Hex map:

*What does this communicate to you?*

There is more debt in the Eastern United States. 

*Is there anything confusing about this?*

The location of each state isn't where expected, due to the uniformly sized hex tiles.

Debt by Loan Type animation:

*What does this communicate to you?*

Debt is increasing over time. Direct loans seem to have gotten more common than the other two types.

*Is there anything confusing about this?*

The animation distracts from looking at what each color means. I'm also not sure what each different type of loan means, or why that matters for the message of the data. If I want to check what the sizes correspond to, I have to pause the animation and then scroll back to the data point I'm interested in seeing the size of. 

## Final proposal for the authors at Forbes dot com
For my final proposal of each data visualization, I implemented some the feedback I got from my interviews. Specifically, I changed the color scheme of the map - I hadn't thought about the $18k values looking like no debt compared to the darker red, so I thought this was a good change! I also decided to cut out the time animation entirely, as I agreed that it was too much to look at and distracted from the message I was trying to convey. I also created an area plot, as one interviewee suggessted, instead of a line graph for the debt by loan type over time data. I liked the way this change in visualization type conveyed the sense more visually that student debt is a HUGE dollar amount. I also chose to check statistics for what college tuition costs these days, compared to 15 years ago, to attempt telling a more complete story with the data. I didn't feel it was necessary to actually show how this data changed over time; I thought a callout statistic in the subtitle of the graph communicated effectively the point I was trying to get accross. While I didn't originally intend to include my original sketch idea of the line plot in my final data visualizations, I ended up making a cleaner version of it for the final plot suggestions below, as well, using some of the general stylistic critiques I got for my other two visualization ideas. I felt the comments about the loan types being confusing were valid, but I also feel that readers of Forbes magazine are generally business-minded, ecomonically interested people, so I wouldn't be surprised if many of them actually *do* know what all the nuanced differences in the loan types are. Overall, I feel these data visualizations, while not exceptionally fancy, do a much better job than the visualizations in the original Forbes article at actually using data to tell a story or get a message across, rather than presenting a reader with a bunch of raw data.

<div class="flourish-embed flourish-scatter" data-src="visualisation/15086564"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<div class="flourish-embed flourish-chart" data-src="visualisation/15089512"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<div class="flourish-embed flourish-map" data-src="visualisation/15091661"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

***
_Thank you for taking the time to check out my work!_
