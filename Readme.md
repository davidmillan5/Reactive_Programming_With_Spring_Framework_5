 # Reactive Programming with Spring Framework 5

This are my notes and code from the course on Udemy from John Thomson that you can enroll on the following link 

[Reactive Programming with Spring Framework 5](https://www.udemy.com/course/reactive-programming-with-spring-framework-5/)

![img.png](img.png)

One of the most interesting new features in Spring Framework 5 is Reactive Programming.

Reactive Programming is an important paradigm shift from the traditional object oriented programming commonly used with Java.

Reactive Programming adopts an immutable / functional style (which is fully explained in the course!).

While Reactive Programming may not be an automatic way of making your code faster, it can help your code scale up better. Especially if you are dealing with streams of data.

In side this course, you will first learn the fundamental concepts of Reactive Programming. You'll learn why immutability and functional programming are important to Reactive Programming.

Next, you'll get hands on experience with building a Reactive application to stream 'movie events' leveraging the Reactive data types and WebFlux - both new to Spring Framework 5.

These exercises help get you comfortable using the Reactive Programming APIs and functional programing style.

Following is a whole section on using Spring Web Client. This is the reactive web client introduced in Spring Framework 5. Spring Web Client is the reactive equivalent of Spring RestTemplate.

While Spring Web Client is the equivalent of Spring RestTemplate, Spring Web Flux is the equivalent of Spring MVC. You will learn how to use Spring Web Flux to create a RESTful API.

The JDBC API for accessing relational databases is blocking, and therefore not compatible with Reactive Programming. R2DBC is the reactive equivalent of JDBC. You will see how to use Spring Data R2DBC and reactive types to perform CRUD operations against a Relational Database.

Spring Webflux also introduces a new functional style API for defining endpoints. You will see how to use this functional API to configure a RESTful API. Hello functional programming, good by Spring MVC annotated controller classes!

Where Reactive Programming really excels is dealing streams of data. You will see how to build a stock quote streaming service. Then how to stream those stock quotes into a MongoDB document store. And how to stream stock quotes to RabbitMQ Messages.