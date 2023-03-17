# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: APIs

[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. REST stands for Representational State Transfer which was originally an architectural approach to designing web services.
2. REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.
3. Resource identifiers are URl that uniquely identifies that resource. This could be something like a website URL such as google.com
4. The most common verbs or operations are GET, POST, PUT, PATCH, and DELETE.
5. URIs should be based on nouns (the resource) and not verbs (the operations on resource).
6. A good URL would be https://adventure-works.com/orders or www.buyhats.com
7. Chatty APIs impose more of a load on the web server which is NOT A GOOD THING.
8. A successful GET method typically returns HTTP status code 200 (OK)
9. An unsuccesful attempt will get a HTTP status code 204 (No Content)
10. If a POST method creates a new resource, it returns HTTP status code 201 (Created)
11. If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content)

## Bookmark

[RegExr](https://regexr.com/) Pay particular attention to the cheatsheet

[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

[Regex 101](https://regex101.com/)

## Class Notes

## Things I want to know more about
