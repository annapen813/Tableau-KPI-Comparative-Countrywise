# KPI-Comparative-Study-Countrywise

Tableau Dashboard

DESCRIPTION

Problem Statement:
Create a dashboard to compare all the parameters mentioned above for different countries, to strategize market penetration and to target new customers.

Dataset's
Primary Dataset – Insurance Sample Dataset
Secondary Dataset – Global Financial Development Database

Note: Use Data Blending with Relationships between Country Code, Country, and Year

Dashboard Description
A geographic map showing countries field. Color the map based on Income column from the secondary dataset which includes a fileter on Income group.

Also, I have included a webpage to show data from world bank webpage driven by an URL action from geography graph. Based on the country names, the map will act as the trigger  https://data.worldbank.org/country/<country>?view=chart and the corresponding data will be shown.

Created a KPI Table to show the comparison between the selected period, and created two parameters for Year and Categorywise selection. Based on the categoy, the title will get updated.

Category Parameter - Life Insurance Share, Market Share, Penetration, Ratio of Reinsurance Accepted & Retention Ratio, which will help to create a calculated field to calculate the Growth %, which will be shown on the table. Based on the Growth %, Growth Indicator Shapes will be generated.

Growth indicator to display Negative, No Change and Positive as values and corresponding shapes against it. I have also created a trend line to show the selected category values.

Dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well. Formatting to be done appropriately

 
