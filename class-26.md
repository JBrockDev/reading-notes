# Class 25 - Reading Notes

## NoSQL vs SQL

| SQL | NoSQL |
| --- | --- |
| Relational | Non-relational |
| Table based | Key-value pair based |
| Predefined schema | Dynamic schema |
| Vertically scalable | Horizontally scalable |
| Uses SQL | Uses UnQL |

1. SQL databases are best for non-hierarchical data storage.
2. Financial institutions typically use SQL as there's more data safety (less anomalies) and wider variety of queries as well as better transactional ability.
3. NoSQL databases are best for hierchical data that has little to no cross-table (in the event of being compared to SQL) dependencies.
4. A real world example of NoSQL would be an email or messaging application.
5. SQL is best for hierachical data storage.
6. For scalability, the easiest would be NoSQL as you just have to add more servers. SQL you would have to add more CPU, RAM, SSD, etc.

## SQL vs NoSQL Video

1. SQL stands for Structured Query Language.
2. A relational database is a database with tables that supports SQL.
3. A relational database works with tables.
4. A schema is a blueprint of fields that are to be expected for each entry into the table.
5. A NoSQL database is a database without a schema.
6. NoSQL databases have records that don't necessarily have to have all of the same properties as one another.
7. Inside of a Mongo database are entries similar to JSON objects.
8. MongoDB is more flexible with data due to not needing everything in a collection to have the same fields/properties.
9. The disadvantage of of NoSQL is for a product that needs to write often, it will have to update in multiple places.
