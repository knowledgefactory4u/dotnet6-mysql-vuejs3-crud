# .Net 6 + MySQL + Vue.js 3 CRUD Application Example

# After completing this tutorial what we will build? 
We will build a full-stack web application that is a basic User Management Application with CRUD features: 

• Create User 

• List User 

• Update User 

• Delete User 

• View User

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhCR9PQOd8nl8T6JmXxUPdQtAXsrYOC5R3IwN6g1Lq1rTyTk3EYPiFd3_aNubV2vknuCbsNShnD5qIFXmUl0EItyALCn24oQEswgpVt2y2ngVXgizpcsRD5AgaDIl0TFBTtazeRPQ6gUnPLF59q63y0VIGFIi0ucap54BZStLJjlMmCDcBXR4jPEm0-xQ/s1042/uinetmysqlvue.png">


# Local Setup and Run the application

<h2>Create database and table</h2>

```CREATE DATABASE testdb;```

```
CREATE TABLE users(
 id INT PRIMARY KEY AUTO_INCREMENT, 
 first_name VARCHAR (20) NOT NULL, 
 last_name VARCHAR (20) NOT NULL, 
 email VARCHAR (20) NOT NULL 
);

```

<h2> Download or clone the source code from GitHub to the local machine</h2>

<h2> Backend</h2>

You can start the api by running ```dotnet run``` from the command line in the project root folder (where the WebApi.csproj file is located)

OR

You can also start the application in debug mode in Visual Studio by opening the project root folder in Visual Studio and pressing F5 or by selecting Debug -> Start Debugging from the top menu, running in debug mode.

<h2>Frontend</h2>

```npm install```

```npm run serve -- --port 8081```

<h2>From the browser call the endpoint http://localhost:8081</h2>
