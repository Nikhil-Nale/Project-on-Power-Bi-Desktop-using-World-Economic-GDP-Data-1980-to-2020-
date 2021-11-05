# Project-on-Power-Bi-Desktop-using-World-Economic-GDP-Data 1980 to 2020 : 

Here I use powerBI Desktop for extracting the data from the web, transforming the data, loading the data to the Power BI, and lastly creating reports in PowerBI Desktop and  Publish report to powerBI service.

# Steps for data connection, data preparation and data reporting :--

1. Connection with the Data:- 
Open the Power BI Desktop on your laptop On the left-hand side click on Get Data ->Search Web on the left side and then select it -> Click Connect -> By default it will be selected Basic (don’t change that) and under that in the URL section paste the above link and click OK. As soon as you click OK, you’ll see the Navigator (here you need to select the right table for your dataset, which is table 5) -> Select Table 5 -> On the right side you can see the table view of it -> Click Transform to perform data cleansing and preparation.

2.Transforming the data in Query Editor (it is used for data cleaning and data pre-processing)
Turning 2nd row to the column names and removing the 1st row(as it is irrelevant) To do this go to Home ribbon -> Remove Rows -> Type 1 -> click OK. Now, go to Home -> Use the first Row as Headers. You will observe that the 2nd row is changed to headers.

3.Data Reporting —
Go to data view from report view on the left side and change the data type of country from text to country (as it is provided by power bi). To do this select country and then go to Column tools ribbon on Top or Modelling tool depends which version of power BI you are using -> Data Category -> Country
On the right-hand side, you can see all column names under the Field column on the right-hand side of the screen.
Select any visualization type of your choice -> Select Bar chart 📊(later we will change it to World Map 🌎 ) and then start making the visualization.
To make visualization drag GDP top values, year to the axis, and country to legend (values, axis, legend all are available below visualization types).
Now on the left of the visualization column, you can see filters, we will target the top 10 countries’ GDP. To do that select country is (All) and under the filter, section changes the filter type from basic filtering to top N and type 10 and drag GDP to value and click Apply.
Now you can change the Bar Chart 📊 to World Map 🌎 from Visualisation panel on the left side of the report view.

