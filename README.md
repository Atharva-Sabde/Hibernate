# Hibernate
Hibernate theory + Code for quick interview prep.
> Hibernate is java framework that simplifies the development of java application to interact with database.
> 

Why hibernate?
->  Hibernate is an ORM ( object relation Mapping )  tool for java. 
    Using this we can map java Classes to database tables and even java datatypes to sql datatypes.

- Saves lot of time in developing database extensive applications , so  we can focus more on business logic.
- Write CRUD operations without actually writing SQL queries.
- HQL allows to write Object Oriented Queries for advanced operations
- Implementation of JPA , so has high interoperability with other java EE apps.

### Features of Hibernate:

![image](https://user-images.githubusercontent.com/67774570/137636678-d901a3c6-c032-415f-ab89-22b2612329b8.png)

1. ORM
    - allows mapping of java domain objects into tables and vice versa.
    - business logic is able to change database entities via java objects
    - speeds up overall development process by transaction management,  auto primary key generation and managing DB connections
2. Idiomatic Persistence
    - Any class that follows OOPs principles can be used as a persistent class
3.  JPA Provider
    - JPAs are specifications for accessing and managing data between java objects and RDBMS entities.
4. Easy to maintain
    - it do not require special tables or fields, it generates sql at system initialization time , and is much more quicker and easier than JDBC
5. High performance and Scalability. 
    - supports different fetching strategies , lazy initialization , optimistic locking etc to achieve high performance
    - scales well in any environment.
