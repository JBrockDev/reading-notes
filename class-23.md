# Class 23 - Reading Notes

## API Design Best Practices

1. REST stands for Representational State Transfer.
2. APIs are designed around a resource. (Commonly a database)
3. A resource has an URI identifier, https://starbucks.com/orders/42
4. The most common HTTP verbs are GET, POST, PUT, DELETE ... PATCH is far less common, but somehow still considered one of the most common.
5. A URI should be based around a collection.
6. Example of a good URI: https://jbrockdev.com/logs
7. A chatty API is one that requires a lot of requests each for small resources rather than grouping things commonly needed together into a larger response.
8. A GET returns a 200 for success.
9. A GET returns a 404 for not found.
10. A POST returns a 201 for success.
11. A DELETE returns a 204 for success.

1. Match own name to RegEx
  - /^Jonathan$|^jonathan$
