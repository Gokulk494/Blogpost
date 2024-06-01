Application made using:
Java 8,
Spring Boot v2.2.6,
Spring Web,
Spring Data JPA,
Spring Security,
H2-in-memory-database,
Lombok,
Thymeleaf
Maven.

Unregistered/anonymous blog users can view all posts and comments;
Registered and logged in users (Authenticated users) can add new posts, view only their own posts, edit or delete them (CRUD functionality);
Users can write comments to particular posts by own or other users;
Validation for creating new posts, body must not be empty, title must have length of 7 by default and other;
Spring Security authentication and authorization rules ensures that users only able to edit or delete their own posts;
Front-end made using Thymeleaf templates.

Made an effort to write clean OOP code to my Date.past() best understanding, like separation of concerns and encapsulation of internal workings of the class to hide details from outside while providing a simple interface to work with a class and there should be no to little pain adding new functionality.
(Please be forgiving it was my first Spring app and first steps into OOP)
