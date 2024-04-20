# EccomerceBackend-Springboot
The web application created is for an online clothing store that will allow users to buy and order clothing online. The application backend was built with the Spring Book framework and a SQL database to store and retrieve data. REST APIs are utilized to handle HTTP requests and responses with the use of @RestController, @GetMapping, @PostMapping, @PutMapping and @Deletemapping annotations.

The annotation provided by spring boot framework has been used as below. 
•	@RestController annotation has been used to make the class a controller.
•	@Autowired annotations are used to resolve dependencies
•	@Getter , @Setter @Entity annotation has been used to connect the bean class to particular tables in the database.
•	@joincolumn annotation as a join column for an entity association or an element collection
The application consist of two type of roles admin and local user. Users must first register into the system in order to get started with the online clothing store. The functionalities and contents that users can have access to are limited based on their roles. When the user logs in to the system, it will redirect user to the homepage according to the user role.


