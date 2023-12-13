# Video 2023.04.22
# Layered Architecture - MVC 2

# layered architecture 
  divide data into layers that came from the front end
  front-end request comes as an HTTP request (JSON object)

# Web.xml
  is the first request identifier 
# Dispatcher servelet/ front controller 
  use handler mappings  
# @CrossOrigin 
  get all requests
# @CrossOrigin("localhost:4200")
  is used to get only requests coming from "localhost:4200"
# layer structure

<img src="https://github.com/molindu/IMPORTANTS/blob/main/images/layered_archtecture.jpg" alt="GitHub Logo" width="450"/>


* controllers used to handle crud operations, business logic
* controller recieved the data match to DTO
* @RequestBody -> JSON request convert to java
* @RestController(simplify the creation of RESTful web services. )
    * @ResponseBody
    * Controller
# Service layer do database saving logics
  * Service classes should call by creating objects in controller methods.
* Singleton method used to use one object to many time.
* Tightly couple should be loosly couple.
* dto object -> controller -> service(dto object)
* interface inside has abstract method (that methods has no body)
* interface has only method declaration.
# service class should implement through interface.
# @Service used to service class.
# Autowired used to implement dependency injections.
  * used to get implementataion of another class

* if we want to implement and different classes @ qualifier used

# controller - API
# Entity - Modal
# Service - Request Layer



