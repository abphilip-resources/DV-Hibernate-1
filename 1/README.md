# Hibernate: Notes

### Abbreviations       
    JPA     : Java Persistence API
    ODBC    : Open DataBase Connectivity
    JDBC    : Java Database Connectivity
    ORM     : Object Relational Mapping

---

### Setup links
- [MySQL Workbench](https://dev.mysql.com/downloads/)

---

### Object relational Mapping
**`A way to map your objects to underlying database tables`**

ORM simplifies programmatic access to databases, bridging the gap between objects and relations. This helps the application to move seamlessly between an object oriented world and the relational database world beyond their impedance mismatch.

It also provides the application an object-oriented view of the database, allowing it to use OOPs concepts as well as implement database transactions.

---

### Hibernate framework
An ORM based on the spring framework. It implements the JPA specification providing a consistent way to access and manipulate data in a database. It provides us with a set of tools and features to help us to create a robust application.
- **Hibernate Validator** : A library that provides a set of validators for Java beans.
- **Hibernate Search** : A library that provides a search engine for Hibernate.
- **Hibernate OGM** : A library that provides a Object Graph Mapper for Hibernate. Used for NoSQL databases.
- **Hibernate Query Language** : A library that provides a query language for Hibernate.
- **Lazy loading** : Used to load data from the database only when it is needed.
- **Multiple levels of caching** :
    + First level caching within session.
    + Second level caching across sessions. 
- **Optimistic locking** : Used to prevent concurrent updates to the same record.

---

### JPA - Java Persistence API
Specification for persistence providers, implemented by ORMs. It is not an implementation. Database at bottom, then an ORM framework and finally a persistence provider. It is a specification to standardize ORM behaviour. It provides metadata annotations to map the database tables to Java classes as well. 

- Name of the object = Name of the table.
- Fields of the object = Columns of the table.
- Each table row is mapped to a Java object.
- Primary keys to identify objects.

These allow CRUD operations to be applied on objects.