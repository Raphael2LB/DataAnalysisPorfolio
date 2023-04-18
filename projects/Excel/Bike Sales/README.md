BIKE SALES ANALYSIS 

The purpose of this analysis is to explore new lead marketing for a company active in the bicycle industry.
To do this, we will use the "bike_buyers" dataset from https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx This is information pertaining to bike buyers from all over the world .

Given the purely demographic data at our disposal, we should be able to draw up a “persona” which will make it possible to develop a first base useful for strategic decision-making for the company concerned.

The entire project was carried out in Excel.
The end result is a dynamic dashboard that can be filtered by continent using a segment.
To consult the dynamic dashboard, go to “Bike_Sales.xlsx” present in this folder.

![image](https://user-images.githubusercontent.com/130085381/232844588-38305eb6-4782-4f70-b3cd-bc9010efb951.png)


1/ DATA CLEANING :

The first step of this project consisted of cleaning the dataset.

-Removal of duplicates

-Transformed the "Marital status" and "gender" columns to show their full meanings rather than initials.

-Creation of a new column "Age Bracket" which groups the ages into 3 main groups, in order to facilitate the reading of future graphs.


2/ INVESTIGATION:

The second step was the search for interesting information to highlight in the final dashboard.
Every charts were created thanks to pivot tables displayed in "Pivot Table" tab in the Excel file.

First, I decided to create a bar chart that shows the distribution of bicycle sales according to the level of study of the buyers. We see that higher the level is, the more people buy. However, the trend is reversed when buyers have a “graduate” level.

![image](https://user-images.githubusercontent.com/130085381/232845796-94a0cf39-ff99-4700-8e23-6a06eb104e95.png)

Then, I drew up a line chart that shows the trend of buying bikes according to the following age groups:
Youth: 25-30
Middle-age: 31-54
Old: 55+
It can be seen that regardless of region, most buyers are of middle age.

![image](https://user-images.githubusercontent.com/130085381/232845597-f7a47efc-4562-4c3d-8c99-298862483abf.png)

Then I decided to create two Pie charts in order to visualize the distribution of bike buyers by marital status on the one hand, and by gender on the other.
It shows that across all regions, there are slightly more single buyers (52%) than married buyers.
And there is parity between men and women. 50/50.

![image](https://user-images.githubusercontent.com/130085381/232847499-b512f620-a5b0-4c53-9512-f9f105fb8e5d.png)
![image](https://user-images.githubusercontent.com/130085381/232847651-25239cfa-b108-4d8d-8a97-c2060193c709.png)

Then, the parameter of the children seemed to me interesting to investigate. We have therefore created a histogram in order to visualize bicycle purchases according to the number of children per household.
The graph is represented with a trend line indicating that the international trend is that the more children there are in a household, the fewer bicycles are purchased. Note that single individuals have been discarded in order to make the graph viable.
We find that married individuals buy when they have between 0 and 1 children, the trend is decreasing as the number of children per household increases.
 
![image](https://user-images.githubusercontent.com/130085381/232847729-c57273da-09ba-4e3c-ba75-94fd0fcf9692.png)

Finally, we have highlighted the home/work distance traveled by the different individuals, most are between 0 and 1 Miles, the trend is constant and less thereafter.

![image](https://user-images.githubusercontent.com/130085381/232847766-20ff29de-711e-4e56-ae2a-d234a18166b5.png)


3/ CONCLUSIONS:

At the end of this analysis, we can draw up a persona for a company selling bicycles: the married executive from a big city, with a child.

![image](https://user-images.githubusercontent.com/130085381/232847789-9995f0b6-e973-4f7e-84ca-b814c4feb8a0.png)

We make this conclusion following the analysis of international data, however, it is not excluded that our persona varies from one continent to another.
It is for this reason that we provide a filter by continent, in order to allow the refinement of the investigations by the direction of our company.
