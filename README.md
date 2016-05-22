# scraping-microservice-java-python-rabbitmq

A sample web scraping service demonstrating how to build a message driven application using RabbitMQ. The application consists of three parts: front-end developed in Knockout.js, that is communicating with a Spring Boot Java api, which in turn is offloading scraping tasks to a Python microservice.

![Architecture](http://www.bernhardwenzel.com/assets/images/scraper-microservice/scraper-microservice.jpg)

Original blog post: <http://www.bernhardwenzel.com/blog/2015/04/10/post-spring-boot-rabbitmq/>

Requires java 1.8

in Postgres , we have to create a new user name root for creating db.

Rabbitmq configuration requires user name password guest/guest in Rabbitmqconfiguration java file and the same has to be updated in worker.py

in these two places  the host ip has to be updated with the actual ip or the ip 127.0.0.1
