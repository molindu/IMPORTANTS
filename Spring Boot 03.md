# Video(2023.04.29)
# Repositories use as Interface calss 
# Repository class define using 
```txt
  * @Repository
  * @EnableJpaRepository
```
# repo classes should extend using JpaRepository <entity-name,id-type>
# Orm(object relational Mapping)
```txt
  is a method that manipulates databases data using Object Oriented Language 
* can work without using sql queries
```
# JPA
```txt
* is a specification
* hibernate - is a orm tool, framework (JPA implementation)
    * Open source light weight orm tool
    provide object relational persistance & query services
```
# hibernate used to match java object to database data and save it.
# Jpa - reponsible for relational databases manage.
# should use @Autowired repo to service impl
# should give database operations to repo
# should assign customer dto to customer entity
# constructor calls when object initialize
# customer conttroller -
```txt
    * customer service IMPL
```
# Customer Service IMPL
```txt
  * should @Autowired customer repo to service impl
  * when update data
      should asign customer dto to customer entity
      then pass customer entity object to save method in customer repo through service impl
```
# save data - @PostMapping
# Update data - @PutMapping

