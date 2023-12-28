<head>
  <link rel="stylesheet" href="styles.css">
</head>

<h2 style="red-highlight {">This text will be highlighted in red.</h2>

# ORM (Object-Relational Mapping): 
```txt
* Hibernate is an ORM framework that maps Java objects to database tables and vice versa. 
* As a backend developer, you should understand how Hibernate simplifies database interactions 
  by allowing you to work with Java objects rather than SQL queries directly.
```
# Entity Mapping: 
```txt
* In Hibernate, you define entity classes that represent your database tables.
* You should know how to annotate these classes with Hibernate annotations such as @Entity, @Table, @Column, @Id, and
  others to specify their mapping to the database schema.
```
# Session Factory and Session: 
```txt
* Hibernate uses a SessionFactory to create Session instances, which represent a single unit of work with the database.
* You should understand how to configure and use the SessionFactory to manage database connections and transactions.
```
# Transaction Management: 
```txt
* Hibernate supports transaction management for database operations.
* You should be familiar with how to begin, commit, and rollback transactions using Hibernate's transaction API
  or declarative transaction management with Spring Boot.
```
# JPQL (Java Persistence Query Language): 
```txt
* Hibernate provides JPQL, a query language similar to SQL but operates on entity objects rather than
  database tables.
* You should know how to write JPQL queries to retrieve and manipulate data from the database using
  Hibernate.
```
# Cascade Operations: 
```txt
* Hibernate supports cascade operations, which automatically propagate changes from parent entities to
  associated child entities.
* You should understand how to configure cascade types such as ALL, SAVE_UPDATE, DELETE, etc., to manage
  the lifecycle of related entities.
```
# Fetching Strategies: 
```txt
* Hibernate offers different fetching strategies (e.g., eager fetching, lazy fetching) to control how
  related entities are loaded from the database.
* You should understand the implications of each fetching strategy and choose the appropriate one based
  on your application's needs.
```
# Integration with Spring Boot: 
```txt
* As a Spring Boot developer, you should know how to integrate Hibernate with Spring Boot applications
  using Spring Data JPA or plain Hibernate APIs.
* This includes configuring data sources, transaction management, and entity management within a
  Spring Boot environment.
```
# Performance Considerations: 
```txt
* Understanding how Hibernate generates SQL queries, caching strategies, and database indexing can help
  you optimize the performance of your
  application when working with large datasets or complex queries.
```
# Error Handling and Logging: 
```txt
* Finally, it's important to be familiar with handling exceptions and logging in Hibernate.
* This includes understanding Hibernate's exception hierarchy and how to log SQL statements and other relevant
  information for debugging purposes.
```
