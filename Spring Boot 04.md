# Video (2023.05.14)
# @GetMapping
  * Params name should equel to method param names.
# when the name doesn't match
  *use (@RequestParam(value="id") int customerId) in the method
# Video (2023.05.19)
swagger 2 mvn 
swagger ui
* When use third party libraries create config package and create inside configuration class.
# if swagger not worked
 * add application Properties
   * Spring.mvc.Patchmatch.maching-strategy = ant-path-matcher
* config -> SwaggerConfig.java
```java
  //SwaggerConfig.java
  
  package com.springbootacademy.springboot10pos.config;

import org.springframework.context.annotation.Bean;
import springfox.documentation.builders.PathSelectors;
import springfox.documentation.builders.RequestHandlerSelectors;
import springfox.documentation.spi.DocumentationType;
import springfox.documentation.spring.web.plugins.Docket;

public class SwaggerConfig {
//
    @Bean
    public Docket SwaggerApi(){
        return new Docket(DocumentationType.SWAGGER_2)
                .select()
                .apis(RequestHandlerSelectors.any())
                .paths(PathSelectors.any())
                .build();
    }
    //
}
```
* next goto localhost:8082/swagger-ui.html
