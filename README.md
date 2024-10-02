## Lab 6

This lab will use a subset of the Seattle Police 911 calls data set [http://math.montana.edu/ahoegh/teaching/stat408/datasets/Seattle_911_062016.csv](http://math.montana.edu/ahoegh/teaching/stat408/datasets/Seattle_911_062016.csv). 

```
library(tidyverse)
seattle <- read_csv('http://math.montana.edu/ahoegh/teaching/stat408/datasets/Seattle_911_062016.csv')
```


### Q1. (5 points)
Create a figure to address which hours of the day have the most 911 calls (using the `Event.Clearance.Date`).



### Q2. (5 points)
What percentage of the 911 calls are the result of an ALARM, (using the `Initial.Type.Description`).


### Q3. (10 points)

Create a figure telling a story from this dataset using the `Event.Clearance.Group` variable. Make sure to include appropriate axes, titles, and include an annotation.

When creating your figure, note that there are 40 separate groups. Consolidate these into meaningful categories.


