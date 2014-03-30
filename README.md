Miami University and Association of Public and Land-Grant Universities d3.js Visualization
========

Here you'll find the source code for my d3.js visualization of public salary data, as well as the
data this was generated off of. I received the data on request from Miami University, Oxford, in
2012. 

There was some intermediate cleaning of the data I received from Miami:

- There are a handful of missing values, particularly in 2004. Rather than impute these, I've
excluded them from this analysis.
- Additionally, departments change names, split, merge, and disappear entirely. I've done my best to make
these changes self-evident in the data through my labels.
- I received nominal wage values, subject to what I like to call the 
["These Amps Go Up to 11"](http://en.wikipedia.org/wiki/Up_to_eleven) 
problem&#8212;nominal values are simply relabeling of information that actually matters. 
In order to highlight meaningful changes, I converted these to real wages using 
[Oregon State University's freely available inflation data](http://oregonstate.edu/cla/polisci/individual-year-conversion-factor-tables) 
for 2013, the most recent year of data available as of this analysis.

I'll post the wage data before I cleaned it in Excel to this repository, as well.
