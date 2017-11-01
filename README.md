

# JDBC Project Overview

Goal:
Developing a Java application that interacts with a local SQLite database using the Java Database Connectivity (JDBC) interface.  This is done in a way where there is no transfer of data between the database server and the client running Java. The entire computation is carried out using SQL commands on the server side.


======================================================


Database Schema:
The database will hold data about direct flights between cities on given airlines. The database has one “Flight” with attributes “Airline”, “Origin”, and “Destination”. (All attributes are non-null character strings)


======================================================


Final Output:
A table “Connected” with columns “Airline”, “Origin”, and “Destination” and “Stops”. This table contains the tuples <A, city1, city2, N> where N is the minimum number of stops needed to reach city2 from city1 by flights on airline A.
