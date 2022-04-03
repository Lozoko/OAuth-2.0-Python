# Implementation of OAuth 2.0 protocol using Python and web applications

Final project for Design Patterns - subject of the 3rd year of studies.

The goal was to implement OAuth 2.0 protocol using Python and present its functionality using three different web application - written using Vue.js and JavaScript \
In addition a lot of emphasis was put on using at least three different design patterns (in this project - Builder pattern, Facade pattern, and  Data Access Object pattern) as well as paying attention to good coding practices

Backend was written using Python and FastApi. There are overall four servers. The main server is responsible for authorization aspects. It can log in or register users, allow for client's application's authorization, check for required scopes to perform a request on some data, generate, introspect and revoke authorization tokens, both by the will of users and system administrators. Three remaining servers are acting as resource servers. They accept requests from client applications and reply with the response - depending on the permission given to web application.

Every server has a separate database in which it stores necessary data. PostgreSQL was used in this project. Communication with the database was written according to Data Access Object pattern

Frontend was written using Javascript and Vue.js. There are three different web application. One for managing tasks to do, one for saving private notes, and one for writing publications on users' forum. In addition, there is also a frontend web application for authorization server. Users can log in or register there, revoke authorization tokens and add new client applications.

The project was written thanks to the contribution of these people: \
Łukasz Ślęczka \
Szymon Frelich \
Elżbieta Cymerys \
Konrad Kowalczyk 
