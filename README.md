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

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%201.png" width="700"/>
</p>

### **The results...**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%201%20-%20Results.png" width="700"/>
</p>


With this data now accounted for in our dataset, it's time to move onto the second deliverable and recalulate the following metrics:

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type

### **The District Summary**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20District%20Summary.png" width="700"/>
</p>

### **The School Summary**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20School%20Summary.png" width="700"/>
</p>


### **Top 5 / Bottom 5 Schools**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20Top%20and%20Bottom%20Schools.png" width="700"/>
</p>

### **Average Math / Reading Scores per Grade Level**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20New%20Math%20Scores.png" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20New%20Reading%20Scores.png" width="700"/>
</p>


### **School Spending per Student by School Size**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20Average%20school%20spending%20by%20size.png" width="700"/>
</p>

### **School Spending per Student by School Type**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20Average%20school%20spending%20by%20type.png" width="700"/>
</p>


### **Results**


1. How is the district summary affected?
- The overall passing percentages lowered slightly because the fake, high scores were taken out of consideration to the overall total.
2. How is the school summary affected?
- The overall passing percentages lowered slightly for Thomas High School - high scores were taken out of consideration to the overall total.

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- The sample size of Thomas High School becomes smaller and will affect the overall performance numbers. We can assume they created higher grades for these students, therefore taking them out will lower the overall scores of the school.

4. How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade - The overall grade scores lowered slightly.
- Scores by school spending - The students were still counted however we did not consider their score. The overall school spending did not change.
- Scores by school size - This score was also affected because the school size was altered.
- Scores by school type - The numbers reflected change because the school type containing Thomas High School will have a lower score with those 9th graders not included.




### **Summary**

This analysis was interesting but I also thought the results were somewhat predictable, which can happen in data science. When students try to cheat and change their scores, they are not giving themselves F grades - They are probably giving themselves A and B grades. 

With this in mind, when we alter our data by taking out the 9th graders for a particular school, your overall passing scores will lower, because you are getting rid of the results of higher scores.

The budget per district and per school size will be altered as well as the new data is accounted for and calculated.