![Alt text](image.png)


Microservices refer to a style of application architecture where a collection of independent services communicate through lightweight APIs.

Think of your last visit to an online retailer. You might have used the site’s search bar to browse products. That search represents a service. Maybe you also saw recommendations for related products—or added an item to your online shopping cart. Those are both services, too. Add all those microservices together and you have a fully-functioning application.

So, we have 1,2,3,4, total four services here. NGINX, which is the API gateway, which is the
front end from where all the request comes. And all the communication between micro services happen through this API gateway. This will be an nginx service which will listen for the request and route based on the headers, based on the URLs. So if the request comes on a route, that is if you're just accessing the URL, then it sends to the client microservice which is written in angular. So this loads the front end pages of the website. And for back end data it is going to contact the API service emart API which is written in NodeJS and the URL will be API and NodeJS application. These APIs will need database. And here we are using MongoDB, a NoSQL database. There is also one more integration of another service, books API. And this is written in Java. It uses my SQL database, which is an SQL database and it's URLs WebAPI.
So this is an ecommerce application which has multiple microservice.
