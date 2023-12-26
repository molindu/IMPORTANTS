# 24/08/2023 (Theory session video)

# Enterprise-level application
```txt
    * Large software system application
        complex, scalable, component-based, distributed, mission-critical.

          // Before spring Boot came the story
          java EE(Enterprise Edition ) used as a web application before spring 
          Java SE extended is Java EE 
          java EE is a Specification set introduced by JAVA
          java EE needs to build a web application.
          application servers
            GlassFish
            Apache Tomcat
            JBoss
            jetty
            WildFly
          Too complex
          //
```
# Why did spring come? 
```txt
    * JAVA EE is more complex 
    * Spring simplifies the Java development process
```
# Singleton Design pattern
    one object used for multi-purpose
 
# POJO used to simplify spring
```txt
      * Plain old Java object 
            ex : 1. Entity
        is a object created by using class not extended using any framework extension.
```
# dependency Injection
```txt
      * Used for making tightly couple to loosely couple
```
# Declarative 
```txt
        *aspects & common conventions
```
# can't create objects using Interface 
# transaction?
      when one data depends on two tales every tale should be handled together.<br> That handling process is a transaction. 
# What is a concern?
    behaviour of a class (behaviour == a transaction)  
# cross-cutting concern?
    more than one class repeat one concern 
# OOP?
    If crosscutting concerns exist (one concern used in many classes ) separate them from system services and apply them. That applies mechanism is OOP. 
# Bean?
```txt
    * JAVA Bean - an object that was created by using JAVA spec.
        Qualities of JAVA Bean 
            1. Properties encapsulation.
            2. Has allargs constructor  
            3. Has no-args constructor
            4. Property names camelcase 
    *Spring Bean - Pojo (Plain Old JAVA Object)
    *When using @Component it shows as a bean
```
# Dependency Injection Methods
```txt
      *property injection
      *constructor injection
      *setter methods
```
# Does Servlet do on the web?
   handling request response 

# JPA (Java Persistence API) - 2006
```txt
   * Use Hibernate - Mysql, Java connecting ORM(object-relational mapping) tool 
   * Hibernate native API 
   * JPA
   * Auto query generator 
   * JPQL like sql
   * JAVA Specification
   * implementation 
         JPA implementation (orm tool)
```
# The data access part can be usin
```txt
   1. jdbc
   2. Orm tool
   3. Spring data jpa
```
# 25/08/2023

Stating spring initializer
# Maven? 
   same as gradle
   build tool
Jar - Mobile based
War - Web based
(Jar\War is Artifactor type which is built Maven)

# basic dependency
```txt
   * Spring Web
   *
```
# Appication.properties set up
```xml
      //
      spring.application.name=Mobi-system
      server.port = 8081
      spring.jpa.hibernate.ddl-auto =update
      spring.datasource.driver-class-name = com.mysql.cj.jdbc.Driver
      spring.datasource.url= jdbc:mysql://localhost:3306/mobitel?createDatabaseIfNotExist=true
      spring.datasource.username=root
      spring.datasource.password=1234
```  
# jpa vendor adapter configuration
      
      spring.jpa.database-platform = org.hibernate.dialect.MySQL57Dialect
      spring.jpa.generate-ddl = true
      spring.jpa.show-sql=true
      //

# CONSTRUCTOR 
      is a method which is created by using class name and without return type
      press (Alt + insert) or top task bar -> code -> Generate
# DTO - Data transfer Object
      used to transfer data between layers


      

