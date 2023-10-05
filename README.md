# Webcoreapp
WebCoreapp is a full-stack web application that uses ASP.NET Core,Core API,PostgreSQL,Vue.js.
# Introduction
Webcoreapp is a full-stack application that uses the following technologies:
<br>
ASP.NET Core: A cross-platform web framework that allows developers to build modern, cloud-based web applications.<br>
Core API: A lightweight, high-performance web API framework that is built on top of ASP.NET Core.<br>
PostgreSQL: A powerful, open-source relational database management system.<br>
Vue.js: A progressive JavaScript framework for building user interfaces.
# Architecture
The Webcoreapp architecture is a three-tier architecture, consisting of a presentation layer, an application layer, and a data layer.
<br>
The presentation layer is responsible for rendering the user interface. It is built using Vue.js and communicates with the application layer using HTTP requests.
<br>
The application layer is responsible for handling business logic and processing data. It is built using ASP.NET Core and communicates with the data layer using Entity Framework Core.
<br>
The data layer is responsible for storing and retrieving data. It is built using PostgreSQL.
# Deployment
The Webcoreapp can be deployed to any platform that supports ASP.NET Core, such as Windows, Linux, and macOS. It can also be deployed to cloud platforms such as Azure and AWS.
# Prerequisites
.NET Core SDK: https://dotnet.microsoft.com/download/dotnet-core/3.1<br>
Node.js: https://nodejs.org/en/<br>
Vue CLI: https://cli.vuejs.org/<br>
Navigate to the Webcoreapp directory and run the following command to restore the dependencies:<br>

**dotnet restore**<br>
To start the Webcoreapp, run the following command:<br>

**dotnet run**<br>
The Webcoreapp will now be running on port 5000. You can access the application in a web browser by navigating to <br>http://localhost:5000 .

