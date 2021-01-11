# PyBer_Analysis


**Overview**

The purpose of this analysis is to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. Finally, a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer will be given.

**Deliverable 1: A ride-sharing summary DataFrame by city type**

The following requirements for Deliberable 1 are as follows:

    The total number of rides for each city type is retrieved.
    The total number of drivers for each city type is retrieved.
    The sum of the fares for each city type is retrieved.
    The average fare per ride for each city type is calculated.
    The average fare per driver for each city type is calculated.
    A PyBer summary DataFrame is created.
    The PyBer summary DataFrame is formatted as shown in the example.

Below are the fulfilled requirements for the deliverable. 

**Deliverable 1 Requirements**

1. The total number of rides for each city type is retrieved.

Code and Image
![](Resources/Photo1.png)

2. The total number of drivers for each city type is retrieved. 

Code and Image
![](Resources/Photo2.png)

3. The sum of the fares for each city type is retrieved. 

Code and Image
![](Resources/Photo3.png)

4. The average fare per ride for each city type is calculated. 

Code and Image
![](Resources/Photo4.png)

5. The average fare per driver for each city type is calculated. 

Code and Image
![](Resources/Photo5.png)

6. A PyBer summary DataFrame is created. 

Code and Image
![](Resources/Photo6.png)

7. The PyBer summary DataFrame is formatted as shown in the example.

Code and Image
![](Resources/Photo7.png)


**Deliverable 2: A multiple-line chart of total fares for each city type**

The following requirements for Deliberable 2 are as follows:

    A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
    A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
    A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.
    A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
    An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

Below are the fulfilled requirements for the deliverable. 

**Deliverable 2 Requirements**

1. A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time. 

Code and Image
![](Resources/Photo1_1.png)

2. A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare." 

Code and Image
![](Resources/Photo2_1.png)

3. A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29. 

Code and Image
![](Resources/Photo3_1.png)

4. A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week. 

Code and Image
![](Resources/Photo4_1.png)

5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder. 

Code and Image
![](Resources/Photo5_1.png)


**Deliverable 3 Requirements**

1. Overview of the analysis: Explain the purpose of the new analysis.
*please see introduction for the overview of the analysis for this deliberable requirement.*

2. Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.


3. Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
