This project demonstrates the concept of one-to-many unidirectional mapping using Spring Data JPA and Hibernate. 
In a unidirectional relationship, one entity maintains a collection of related entities, but the reverse relationship is not defined, meaning the child entity has no knowledge of the parent. 
This mapping is often used when the association only needs to be navigated in one direction, making it simpler and reducing unnecessary complexity in the domain model. 
The project leverages Spring Boot to handle configuration, dependency management, and application setup, while Hibernate acts as the JPA provider to 
automatically manage the mapping between Java objects and database tables. 
It highlights the use of JPA annotations to define the one-to-many relationship and showcases how data persistence, cascading, and fetching strategies are handled in such a setup. 
This implementation serves as a practical reference for developers who want to understand how to design unidirectional associations in Spring-based applications 
while ensuring clarity, efficiency, and maintainability in their data models.
