# PROJECT NAME
**Analysing the Covid-19 data with Microsoft Excel**

# PROJECT OBJECTIVES
- To learn how to scrap data from web using **Microsoft Excel**
- To create a visualization dashboard using **Microsoft Excel**

# DATA SOURCING
The data was sourced from COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University
**Link:** https://aka.ms/30DLCOVID19GitHubData

## How to scrap Web Data with Excel
1. Go to the Data tab in the ribbon
2. Under the Get and transform pane, chose **From Web**
3. Enter the URL in the provided dialogue box and click OK
4. In the new dialogue box, click connect to use the data Anonymously
5. Then, choose Load(to load directly to excel without cleaning or transforming) or Transform (to load to the power query for better cleaning, transformation and editings) as required

# DATA CLEANING AND TRANSFORMATION
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

# DATA ANALYSIS AND VISUALIZATION
- The Analysis was done in Excel using Pivot Tables. This made the analysis much more easier and trends were able to be detected 
![EXCEL PIVOTS](https://user-images.githubusercontent.com/57878434/175761881-b2b2aa65-f8ac-45d3-8c57-0b3a38267fa7.jpg)

- The Visualizations were done using the PivotCharts 
![Vizz](https://user-images.githubusercontent.com/57878434/175762086-a12d7b2c-f349-4247-8fd9-1447d611e118.jpg)

## Findings
As at the time and data the analysis was done
- The total Confirmed cases globally was ==> 152951111255
![image](https://user-images.githubusercontent.com/57878434/175761573-656f41d5-f25c-4016-b331-eb5e224355b7.png)
- The total Death globally was ==> 2671774434
![image](https://user-images.githubusercontent.com/57878434/175761611-80d9842a-6de0-472a-a3b7-7e7b9396a10d.png)
- The rate of death was ==> 1.75%
![image](https://user-images.githubusercontent.com/57878434/175761625-60b21bcf-31df-4d66-95c1-b4efdf9cddae.png)
- The top 5 countries with highest confirmations of the virus were:
  - Row Labels	Sum of Confirmed
     - United Kingdom	5831089189
     - France	6496860328
     - Brazil	11996382875
     - India	17485626840
     - US	28371865085
![image](https://user-images.githubusercontent.com/57878434/175761674-f5bd0321-e5cf-4491-a8e4-65978e294daf.png)
- The least 5 countries affected were:
  - Row Labels	Sum of Confirmed
      - MS Zaandam	7307
      - Marshall Islands	3507
      - Antarctica	2079
      - Micronesia	1550
      - Korea, North	38
![image](https://user-images.githubusercontent.com/57878434/175761771-1b683058-202c-472f-9f49-669770e0fc0a.png)

# FINAL VISUALIAZTION
Here is the final visualization 
[covid exce dashboard.pdf](https://github.com/OreBank/Microsoft-30Days-of-Learning/files/8986630/covid.exce.dashboard.pdf)



