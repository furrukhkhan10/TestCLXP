There are 5 components of this project.
4 componenets are to be ran in this project.

This is a step by step guide to run the project.

1) Go to CloudXplor_Server/src/main/java/com/clxpr/demo/
2) Run the file DemoApplication.java which contains the main function. - This will start the backend server

When the server starts, its waiting for a connection to receive data from, which will be provided by the client system

3) Go to CloudXplor_Scrapper/src/
4) Run the file Driver.java which contains the main function. - This will fetch the data from the client system and tranfer to server through socket programming

Stack, Heap, Thread, Hardware resources (Cpu usage etc) and Database resources (read/write spd), the information for these would be sent of the client server to the backend server
This will be stored in a database running on MySQL. The backend server would save information there and retrieve it when sending to the front end application for the user in json format.

5) Go to CloudXplor_DBSCAN_AnomalyDetection_Algo.py
6) Run this file. - This will detect anomaly on some of the data from the db tables and write labels on the column of these tables representing anomaly.

DB Scan is used in this detection algorithm. 
After all the data is fetched, processed and stored.. 

7) Install all required node packages and then type this in console: "npm start"

This will start the front end application.

8) Open browser and start local host. 

The application would be filled with the data fetched from the database through the backend sever. 
