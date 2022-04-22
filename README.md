<p align="center">
    Pyber Analysis
</p>

<p align="center">
    Module 5 for Data Science Bootcamp - Python (Matplotlib & Pandas)
</p>

<p align="center">
    STUDY GROUP FOR MODULE 5 - Ryan Knauff, Cayli Swartz, Marshall Miley, Lora Leonida
</p>

##  **Project Overview**
- I've landed a new job at Pyber, a python based ride sharing app. Coming into my second week on the job, I am already tasked with analyzing rideshare data from January to early May 2019, and create visualizations for the CEO.

<p align="center">
     Pyber data and its purpose
</p>

    1. Why are we analyzing this data?
    2. What is the goal and possible outcomes?
    3. What pieces of data can help build toward and obtain our goal(s)?

- When starting this analysis, it's important to consider who your audience is. In this case, we are presenting to the CEO, who is a former data professional himself. This means that we need to document or analysis and be prepared for any questions he may have. 

## **Analysis**
After inspecting the two csv files, it's important we come up with a list of steps and deliverables. Following this will help us stay focused and avoid confusion, in addition to creating an outline that can be used when presenting your findings.

    1. Import your data into a Pandas DataFrame.

    2. Merge your DataFrames.

    3. Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.

    4. Determine the mean, median, and mode for the following:
        - The total number of rides for each city type.
        - The average fares for each city type.
        - The total number of drivers for each city type.

    5. Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
        - The number of rides for each city type.
        - The fares for each city type.
        - The number of drivers for each city type.

    6. Create a pie chart that visualizes each of the following data for each city type:
        - The percent of total fares.
        - The percent of total rides.
        - The percent of total drivers.

After importing our python modules, reading the two csv files and merging the two datasets together based on the "city" column, it was time to start Deliverable 1. Here is the code I used to create this Data Frame:

### **Deliverable 1:**
<p align="center">
  <img src="https://github.com/lawnshogan/PyBer_Analysis/blob/main/Resources/Deliverable%201%20Code.png" width="700"/>
</p>

### **Deliverable 2:**
<p align="center">
  <img src="https://github.com/lawnshogan/PyBer_Analysis/blob/main/Resources/Deliverable%202%20Code.png" width="700"/>
</p>

## **The results...**

<p align="center">
  <img src="https://github.com/lawnshogan/PyBer_Analysis/blob/main/Resources/Formatted%20Table.png" width="700"/>
</p>


<p align="center">
  <img src="https://github.com/lawnshogan/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png" width="700"/>
</p>

## **Summary**

### **Three business recommendations to the CEO:**
        1. As Urban areas are what seems to be generating the most profit, the data suggests we might be able to increase populatity in rural areas if the rides were not as expensive. 

        2. To boost the total drivers in rural areas, we could incentivise drivers pick up in those areas by increasing their cut of the fare.

        3. Because riders in Urban areas rely on Pyber to get around the city, we could potentially slightly raise prices in urban or suburban areas to make up for the lack of profit in rural areas.
