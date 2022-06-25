# Project Name
Analysing the Covid-19 data

# Project Objectives
- To learn how to scrap data from web using **Microsoft Excel**
- To create a visualization dashboard using **Microsoft Excel**

# Data Sourcing
The data was sourced from COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University
**Link:** https://aka.ms/30DLCOVID19GitHubData

## How to scrap Web Data with Excel
1. Go to the Data tab in the ribbon
2. Under the Get and transform pane, chose **From Web**
3. Enter the URL in the provided dialogue box and click OK
4. In the new dialogue box, click connect to use the data Anonymously
5. Then, choose Load(to load directly to excel without cleaning or transforming) or Transform (to load to the power query for better cleaning, transformation and editings) as required

# Data Cleaning and Transformation
- The data was transformed using Power Query
- Preliminary data cleaning steps were done
  - Promoting headers
  - Changing datatypes where necessary
  - Unpivoting some columns 
- The three datasets were merged to give a very robust dataset

## Issues with Dates
When I loaded and applied the dataset into excel, I noticed that there was errors in my dates columns. This was how i resolved it
- Click on the Data Tab 
- Under the Data Tools pane, choose **Text to Columns**
- The wizard would be launched, choose the file type as Delimited ==> Next
- Choose the delimiter type (comma etc) ==> Next
- In the Choose Column Data Format, choose Date and change the format to MDY ==> Finish

# Data Analysis and Visualization
- The Analysis was done in Excel using Pivot Tables. This made the analysis much more easier and trends were able to be detected 
- The Visualizations were done using the PivotCharts 

## Findings
As at the time and data the analysis was done
-- The total confirmed cases globally was ==> 152951111255
![image](https://user-images.githubusercontent.com/57878434/175761573-656f41d5-f25c-4016-b331-eb5e224355b7.png)



