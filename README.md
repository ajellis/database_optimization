# Database Optimizations

## Description

Takes an already existing database containing over 500,000 unique entries and optimizes it. Adding Indices speeds it up tremendously, and it also adds a search function.



###Data Analysis

#### Total time in Chrome's timeline(without indices)
  28 minutes

#### "Idle" time in Chrome's timeline(without indices)
  27 minutes

#### Time given by the Rails App at the top of the page (without indices)
  1866.8881255 seconds

#### Time given by the Rails App at the bottom of the page (without indices)  
  1868.391176 seconds

#### Total time in Chrome's timeline(with indices)
  18.02 seconds

#### "Idle" time in Chrome's timeline(with indices)
  15.16 seconds

#### Time given by the Rails App at the top of the page (with indices)
  9.495006 seconds

#### Time given by the Rails App at the bottom of the page (with indices)  
  10.587342 seconds


### Results

The App was significantly slower without indices.  Just to generate the page it took over 90 times as long.  To get the info from the database, it took over 200 times as long. Indices sped the process up significantly.  
