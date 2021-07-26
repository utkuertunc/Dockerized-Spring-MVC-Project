# MYSQL Connection with Spring Framework (MVC)

This project can apply CRUD with RESTful API. 
/with MySQL Database.
Used Exception Handling, Custom Exception Handling, Validation-Custom Validation, DTO Mapper Pattern, JPA Auditing.

# Custom Validation
This part is how i define the custom validator annotation. 
The message value has default string message and entegrated my ConstraintValidator with @Constraint.

![validation annotation](https://user-images.githubusercontent.com/38990648/126977533-5720df56-d5cf-4a60-8f64-4222b06b5a47.png)

And this part is my constraint validator class. This parts meaning is "Name must be prefixed with PRD"

.![ConstraintValidator](https://user-images.githubusercontent.com/38990648/126983642-173d3cd0-8482-4a5d-a2a7-4558ea2ade0a.png)


# Custom Exception Handling

HttpStatus.NOT_FOUND error customized to ProductNotFoundException.

![image](https://user-images.githubusercontent.com/38990648/126984352-b059b986-ad16-4bf2-942a-3985a1feabb1.png)

And i can throw it for GET,PUT,DELETE Requests like this;

![image](https://user-images.githubusercontent.com/38990648/126999198-51628380-76e9-49a8-b383-6ce0da579334.png)

# DTO Mapper

This mapper can transform Entity --> DTO and DTO --> Entity

![image](https://user-images.githubusercontent.com/38990648/126999583-75ba4d02-1c33-4ad5-a35b-a7a5e73818d7.png)

# Docker

Here is the Docker Compose file. You can run MySQL server for this project. 
The command is --> `docker compose up`

![image](https://user-images.githubusercontent.com/38990648/127000058-4742d100-284a-42a0-8fff-baa8be3ddcbe.png)



for any question -=> utku.ertunc.mobil@gmail.com
