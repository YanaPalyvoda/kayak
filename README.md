# kayak
This project was realized within the framework of a Data Lead training

## Target:

The Kayak Marketing Team would like to create an application that will recommend where people should plan their next holidays. The application should be based on real data about:

•	Weather 

•	Hotels in the area 

## Actions to do:

•	Scrape data from destinations 

•	Get weather data from each destination 

•	Get hotels' info about each destination

•	Store all the information above in a data lake

•	Extract, transform and load cleaned data from your datalake to a data warehouse


## Result:

•	A .csv file in an S3 bucket containing enriched information about weather and hotels for each french city

•	A SQL Database where we should be able to get the same cleaned data from S3

•	Two maps where you should have a Top-5 destinations and a Top-20 hotels in the area. 


## To run this project:

 - Install the additional packages in your virtual environment:  pip install -r requirements.txt
 
 - Register at https://openweathermap.org/appid to get a free api key
 
 - Create a Mapbox access token and put it in the .mapbox_token file in your local folder to use plotly.express.scatter_mapbox
 
 - Create an AWS acces 

 - Create in AWS RDS  a PostgresSQL  database 

! Please note that the included scripts must be run in order.
