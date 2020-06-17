# ValuationVisualization
---
## Background
Analzye how first and second derivates of valuations metrics correlate stock returns.
### The question we set out to answer

- The initial question we set out to answer was to see whether current valuations justified with the highest growth and growth rates?
Does earnings growth (EPS 1st derivative) correlate with the best stock returns for the year following the annual?
-

---
## Data engineering (brief)

Which API
What info we pulled
How we gathered the data - nested loop, try & except (to skip error), nans, created the DataFrame from a dictionary created from the loop, saved as CSV for speed, created new columns for the data we wanted to analyze, ran derivative functions to populate the columns. Second derivative were calculated using the 1st der. To account for ticker change, the for loop checks an empty list if the ticker is not present. The ticker is appended to the list and the iterates through each ticker.
To account for sign change to avoid nonsensical data. A similar method was followed to check changes between positive and negative numbers. These would be change nans.

---
## What we found

If we picked the stocks with highest yoy growth, how did we do?
Revenue
EPS

If we picked the stocks with the greatest acceleration in growth, how did we do?

