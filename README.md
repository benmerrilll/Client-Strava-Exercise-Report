# Strava Data Exploration and Analysis
by Ben Merrill

There is a growing amount of data in the field of sports and excercise. Strava keeps track of our data as we excercise, helping us to look deeper into the effects of exercising and make better goals. This notebook will be a breif exploration of my client's Strava experience. In this notebook, we use scatter plots, histograms, heatmaps, and interactive mapping to tell the story of my clients exercise adventures in Michigan.

We will make conclusions about exercise time, speed, heart rate vs. total distance, and exercise location.

# Rules Used for Better Figures
In Nicholas Rougier's article, 'Ten Simple Rules for Better Figures' (https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833), we get a look at some of the rules that we can use to create more compelling visualizations. Five of those ten priciples that we use in this notebook are:
 - Know your audience - We know the client well, after having had a few months together. We also know that his goal in this analysis is to better understand his exercise data.
 - Captions are not optional - We thoroughly describe our steps and processes before creating each visualization in order to make an easily recognizable narritive.
 - Do not trust the defaults - This notebook will update many attributes of our figures, helping to better represent the data and our findings.
 - Use color effectively - In each visualization, color helps us encode other attributes in our data, add depth to our plotting and maps, and make our visualizations less binary
 - Avoid chartjunk - Thankfully many of our libraries don't make using chartjunk very easy. We will avoid chartjunk in order to prove our point in a more relatable way
 
# Libraries Used
We will use matplotlib, pandas, numpy, folium, datetime, and altair.

# Conclusion
In this notebook, we saw the location and other attributes of our client's exercise, such as time of day, activity, distances, and habits on shorter or longer runs and bike rides. To explore further, we could measure more correlation of figures, or predict a common path, or new path that could be interesting for the client to explore.
