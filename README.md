# Flood-control-BI-system


In this project, we have built a prototype of a small business intelligence system that gives insights for decision makers about the water level in multiple areas in Putrajaya and Cyberjaya. The system is based on a flood warning system that collects data from various sensors that are planted in specified areas each five minutes and store it in a database. In the database, each row shows the sensor ID, it is area, the date and time, water level in mm, and finally it shows an indicator that indicate if an alarm notification was given by that sensor at that time or not. The sensor gives a notification if the water level exceeded 300mm at that time.


  Since having access to the real sensors in that areas is not possible, we decided to create a dumb database and fill it with fake data to help us build the prototype. We used Python language and some of its libraries to build the database and store it in MySQL database.
	The database will consist of three tables. The first table is the areas table and it will contain one column only which is the areas names. The second table is the sensors table. This table will consist of sensor ID column and the area column. The last table will consist of five column which are sensorID, date, time, rainfall (mm), and the flood alarm notification. 
  
  
 ![alt text](images/table.png?raw=true) 
