# IMDB
This Project contains the database and a REST API for a movie application like IMDB. The database is a relational database.
ASP.Net Core Web API is used to build the API

Below is the endpoint for Movies list
http://localhost:46744/api/movie which will list the movies with movie name, actors name, year of release and producer.
Stored procedure will be called from the Application code to get movie details 
![image](https://user-images.githubusercontent.com/118714450/202985217-46365ad3-f213-4310-a783-288db20806af.png)

Movie can be added in Post method of the same endpoint.
Actors and Producer can be added and viewed from the below endpoint.
http://localhost:46744/api/actor
http://localhost:46744/api/producer
![image](https://user-images.githubusercontent.com/118714450/202984764-534cd790-3e6f-4b8e-9bf1-fa6591bc8d8e.png)
![image](https://user-images.githubusercontent.com/118714450/202984871-0b1895b0-4d70-4c1a-a944-1af78d3d9af5.png)
