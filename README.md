# NH Training MEAN(MongoDB-Express-NodeJS-AngularJS) Architecture

MEAN is an open source JavaScript framework, used for building dynamic websites and web applications. It includes following four building blocks to build an application.

MongoDB − It is a document database, that stores data in flexible, JSON-like documents.

Express − It is web application framework for Nodejs.

Node.js − It is Web Server Platform. It provides rich library of various JavaScript modules which simplifies the development of web applications.

AngularJS − It is a web frontend JavaScript framework. It allows creating dynamic, single page applications in a clean Model View Controller (MVC) way.

mean_architecture.jpeg![image](https://user-images.githubusercontent.com/10463170/111592529-9608b600-87d1-11eb-9149-d937ee0739cb.png)

As shown in the above image, we have AngularJS as client side language which processes the request of a client.

Whenever a user makes a request, it is first processed by AngularJS.

Next, request enters second stage, where we have Node.js as server side language and ExpressJS as backend web framework.

Node.js handles the client/server requests and ExpressJS makes request to the database.

In the last stage, MongoDB (database) retrieves the data and sends the response to ExpressJS.

ExpressJS returns the response to Nodejs and in turn to AngularJS and then displays the response to user.
