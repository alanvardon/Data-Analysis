# Data Visualisation in Google Data Studio using SQL

I undertook a project at work to set up live dashboards nd to enable the company to visualise,
keep track and display the delivery of the companies live campaigns.

I created an SQL query to aggregrate and calclulate the amount of leads that is being received per day per country 
over time. 

(A lead is defined a user who submitted details to find out more information about marketed for university course.) 

This query also calculates the cumulative running total of leads per day per day country.
The main challenge with creating this query, was generating zero values for each country when no leads have been received.

After creating this query, I inputted this into Google Data Studio and connected it to our Production Database 
via Google Data Studio's Postgresql Data Connector, 
this allowed me to produce a live interactive Dashboard of the leads that we are receiving which is now used to monitor live campaigns.

I lastly added the ability to filter via countries and date range.
