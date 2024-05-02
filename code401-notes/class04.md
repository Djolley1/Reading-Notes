# Class 04

1. **What type of database is the best fit for the complex query intensive environment?**

   For a complex query-intensive environment, a **relational database** like SQL is often the best fit. These databases are optimized for handling structured data and complex queries involving multiple tables.

2. **What type of database is the best fit for hierarchical data storage?**

   A **hierarchical database** is the best fit for hierarchical data storage. These databases organize data in a tree-like structure, making them ideal for representing parent-child relationships.

3. **Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.**

   SQL databases are like well-organized libraries where you know exactly where each book is stored. They're great for handling structured data and ensuring it's consistent. However, as the library grows really big, it becomes harder to manage.

   On the other hand, NoSQL databases are more like dumping everything in a big box. It's not as organized, but it's easier to add more stuff quickly. So, when you have a massive amount of data and need to grow fast, NoSQL databases can handle it better.

4. **Among data tables, what is a one-to-many relationship and how do we “relate” them?**

   In a one-to-many relationship, one record in a table can be associated with multiple records in another table. For example, one customer can have multiple orders. To "relate" them, we typically use a foreign key in the "many" side table that references the primary key of the "one" side table.

5. **Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**

   Prior to designing your relational database, it might be useful to **create a diagram** of the database tables and their relationships.

6. **Explain the difference between a primary and foreign key.**

   - **Primary key:** It uniquely identifies each record in a table and ensures that no duplicate records exist. It's typically used as the main identifier for a table.
   - **Foreign key:** It is a field in a table that refers to the primary key in another table. It establishes a link between two tables, enforcing referential integrity and allowing for the creation of relationships between them.

7. **How do we treat keywords and parameters differently in SQL syntax?**

   - **Keywords:** Keywords are reserved words in SQL that have specific meanings and cannot be used for other purposes, like naming tables or columns. They are essential for constructing SQL queries and defining database operations.
   - **Parameters:** Parameters are values that are used in SQL queries to filter, sort, or manipulate data. They are placeholders that can be replaced with specific values when the query is executed. Parameters help make SQL queries dynamic and reusable.

8. **Define normalization within the context of schemas and data.**

   **Normalization** is the process of organizing data in a database efficiently by reducing redundancy and dependency. It involves dividing large tables into smaller tables and defining relationships between them to minimize duplication and ensure data integrity.

9. **Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**

   - **One-to-one relationship:** It's like having one passport linked to one person. Each person has only one passport, and each passport belongs to only one person.
   - **One-to-many relationship:** Imagine a teacher and students. One teacher can have many students, but each student has only one teacher.
   - **Many-to-many relationship:** This is like books and authors. One book can have multiple authors, and one author can write multiple books. It's a bit more complex, so we use a joining table to manage this relationship.
