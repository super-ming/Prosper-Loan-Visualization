## Tableau Project Write Up

### Summary

This visualization explores data on 2007 - 2014 Prosper Loans, which is a peer
to peer lending service. It presents a summary on loan details such as loan
amounts, income levels, loan ratings, interest rates and returns, number of
investors, etc.

### Design

I started by asking questions that I was curious about. How much did people
borrow in each state?  I chose to show the detail with a colored map showing
the number of loans and the median amount borrowed per state. I used color to
show the varying number of loans for each State, and used size to show the
the median amount borrowed. I received feedback to change the points on the map
into a heat map instead, so I changed it into a choropleth using color to show
the median amounts. I added the number of loans to the tooltip and had a filter
bar for it too so users can still view the loan count if they were interested in
that more.

I was also interested in how things changed over time, since there was data from
2007-2014. I had a hunch that people borrowed more after the financial crisis in
2008-2009. It made sense to throw it on a line graph with dual axis as I think
line graphs work the best for time data.

I also used a lot of bar charts as I think they are the easiest to read for
measure type data. Bar charts can also be sorted, whereas things like line chart
cannot be sorted. I added a lot of filters for year and different amounts to
make the story more interactive. Initially I used a pie chart to show income
ranges, just because it was small enough to fit an empty space on one of
dashboards. Later on, I changed the pie chart to a bar chart as suggested from
the feedback received, and moved it to the bottom of the dashboard. I also wrote
multi-sentence captions, but it was suggested to make them as short as possible,
so I shortened them until the full caption was visible without scrolling.

I also felt that having too many bar charts was a bit boring, so I clicked on
"Show Me" to explore other chart types. That's how I ended up with scatterplots,
area chart, and heat map.  

I clicked on "Use as filter" for many of the graphs to make it more interactive.

### Feedback

The feedback that I got from my mentor was 1) shorten the longer stories as much
as possible, 2) change the points in the map into a state heatmap, 3) and change
the pie chart into a bar plot.

### Resources

* https://www.tableau.com/about/blog/2016/11/10-map-tips-tableau-62949
* https://onlinehelp.tableau.com/current/pro/desktop/en-us/maps_howto_choropleth.html
* https://onlinehelp.tableau.com/current/pro/desktop/en-us/maps_build.html
* https://community.tableau.com/thread/145171
* https://community.tableau.com/thread/241693?start=15&tstart=0
* https://onlinehelp.tableau.com/current/pro/desktop/en-us/dashboards_organize_floatingandtiled.html
* https://community.tableau.com/thread/120512
* https://community.tableau.com/thread/151225
