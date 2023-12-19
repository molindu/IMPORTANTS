# Video(2023/12/27)
```java
@GeneratedValue(strategy = GenerationType.AUTO)
```
* used to auto generate key attributes
# ENUM
* The measuring types which are used in an Entity it mention in enum class.
  * @Enumerated(EnumType.STRING)
```java
 @Enumerated(EnumType.STRING)
    @Column(name = "measure_type", length = 100,nullable = false)
    private MeasuringUnitType measuringUnitType;
```
# Lombok Dependency

* @NoArgsConstructor
* @AllArgsConstructor
* @Getter    ->
* @Setter    ->        @Data // common Anotation for @Getter, @Setter, @ ToString
* @ToString  ->

# Model MApper Maven
* Should create Model Mapper Config file and ADD Dependecy
* Model Mapper should @Autowired in ServiceIMPL and should Map.
*   ex: ```java
        Item item = modelMapper.map(itemSaveRequest,Item.class);
        ```
    * itemSaveRequest - converting thing
    * Item.class - converted type
# List<>
  * can't use for modal mapper
    


