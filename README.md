# PyBer Analysis

Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

## Overview of Project

1. ***Deliverable 1***: A ride-sharing summary DataFrame by city type
2. ***Deliverable 2***: A multiple-line chart of total fares for each city type
3. ***Deliverable 3***: A written report for the PyBer analysis [`README.md`]

## Deliverable 1:  A Ride-Sharing Summary DataFrame by City Type
### Deliverable Requirements:
1. The total number of rides for each city type is retrieved. 
2. The total number of drivers for each city type is retrieved.
3. The sum of the fares for each city type is retrieved.
4. The average fare per ride for each city type is calculated.  
5. The average fare per driver for each city type is calculated. 
6. A PyBer summary DataFrame is created.
7. The PyBer summary DataFrame is formatted as shown in the example.
 



### Deliverable 2: A multiple-line chart of total fares for each City type

### Deliverable Requirements:
1. A DataFrame was created using the `groupby()` function on the "type" and "date" columns, and the `sum()` method is applied on the "fare" column to show the total fare amount for each date and time.
2. A DataFrame was created using the `pivot()` function where the index is the "date," the columns are the city "type," and the values are the "fare."
3. A DataFrame was created using the `loc` method on the date range: 2019-01-01 through 2019-04-29.
4. A DataFrame was created using the `resample()` function in weekly bins and shows the sum of the fares for each week.
5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.
 


## Deliverable 3: A written report for the PyBer Analysis


1. **Overview of the analysis** 

**Results** 

    > * The Suburban fares started ~$1,000 -not profitable-fare dropped in March and in mid-April.  
    > * The Rural fares started at ~$200-fares increase and dropped till the end of April.  
    > * The Urban fares start with an average of $1,800 - consistent increase to ~$2,300. 
       
3. **Summary** 

    > Opportunities to expand the business in rural and suburban cities, including hiring drivers 
    
    > The Urban cities - opportunities to expand rides.  
   
    > The Rural cities - opportunity to expand fares 
     > Total Fare by City Type,

    
