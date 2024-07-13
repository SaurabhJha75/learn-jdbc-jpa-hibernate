# learn-jdbc-jpa-hibernate
This repository showcases code implementations—from Spring JDBC’s manual pedaling to JPA’s elegant spellcasting. And then, behold: Spring Data JPA, the modern enchantment that revolutionized how we dance with databases. 

In the ever-evolving world of software development, we’ve witnessed quite the journey when it comes to database manipulation. 

Once upon a time, developers relied heavily on Spring JDBC for their database interactions. It was like the trusty old bicycle—reliable, but perhaps a bit manual. With Spring JDBC, you’d pedal through SQL queries, row mappings, and connection management. It got the job done, but sometimes you’d end up with sore legs (and maybe a few typos in your SQL).

Then, out of the mist, emerged JPA (Java Persistence API). Suddenly, developers found themselves in a magical realm where they could speak the language of objects and let the framework handle the translation to SQL spells. JPA abstracted away the nitty-gritty details, allowing us to focus on our domain models and relationships. 

But wait, there’s more! 

And then, Spring Data JPA stepped onto the stage. It was like JPA had a makeover—glamorous, efficient, and ready to party. Spring Data JPA combined the best of both worlds: the elegance of JPA annotations and the power of Spring magic. Suddenly, repositories became interfaces, and queries were conjured using method names. No more handwritten SQL scrolls; just a few lines of code, and voilà! 

So here we are, my friend, in the era of Spring Data JPA. It’s like having a personal wizard who manages your database connections, fetches entities, and even performs complex joins—all with a flick of the wand (or a well-crafted repository method). 

Remember, though, every chapter in this saga has its purpose. Spring JDBC taught us resilience, JPA showed us elegance, and Spring Data JPA? Well, it’s our modern-day enchantment.

Now, tell me: Which part of this magical journey intrigues you the most? Are you a Spring Data sorcerer, a JPA bard, or perhaps a nostalgic Spring JDBC minstrel? 

## Let's understand the flow of this project
> I have used all the three technologies Spring JDBC, JPA, and Spring Data JPA with the practical coding.

**Spring JDBC**

Spring JDBC is a module of the Spring Framework that provides a simplified approach to working with JDBC (Java Database Connectivity). It acts as a lightweight abstraction layer on top of the JDBC API, handling many common tasks and reducing boilerplate code.

For performing all the operations we use JdbcTemplate.
> **JdbcTemplate:** This is the core class in Spring JDBC. It provides convenient methods for executing SQL queries, updating data, and retrieving results. It handles tasks like opening/closing connections, creating statements, and mapping result sets to Java objects.

**JPA**

JPA stands for Java Persistence API, and it's a framework for object-relational mapping (ORM) that allows Java objects to be mapped to tables in a relational database. JPA is based on the Java programming model and can be used in both Java SE and Java EE environments

When working with JPA, we use the mighty **EntityManager** to perform all our data-storing operations in the database.

> **EntityManager:** In Java Persistence API (JPA), the EntityManager is an interface that manages the persistence of entities in a relational database. It acts as a bridge between the object-oriented world of your application and the relational world of your database.

**Spring Data JPA**

Spring Data JPA focuses on using JPA to store data in a relational database. Its most compelling feature is the ability to create repository implementations automatically, at runtime, from a repository interface. 

It simplifies the and makes the easy to store the entity data into the database without writing any queries.
