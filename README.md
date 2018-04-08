# restAPI-mongoDB
Creating a rest API with Java and Mongo DB. This project was just a way for me to learn rest APIs and connecting to a Mongo database. I utilize the Swagger API docs to use my GET, POST, PUT, and DELETE functions.

## Software
* Eclipse
* Robo 3T

## Built With
* Java
* Apache Maven 3.5.3
* Apache Tomcat 7.0.85
* MongoDB
* Swagger
* Jersey

## Build
1. Clone this repo to your computer
2. If you haven't already, download: Java, Apache Maven, Apache Tomcat, MongoDB, and Eclipse. 
3. Create a workspace in Eclipse and use the directory of restAPI-mongoDB
4. Set up the following properties: 
* Server: Apache Tomcat v7.0
* Targeted Runtimes: Apache Tomcat v7.0
5. Open up your local terminal, navigate to your MongoDB/Server/3.6/bin folder (usually in C:/Program Files).
6. Run the following command in terminal:
```
$ mongod
```
7. In Eclipse, right click the workspace folder, go to "Run as..." and click "Run on Server"
8. An "Hello World" website will pop up in Eclipse. Add '/api-docs/' to the end of the url.
9. You can now use the Swagger API docs to retrieve a user or all users, create a user, remove a user, and update a user.
10. You can monitor your database easier with Robo 3T.
