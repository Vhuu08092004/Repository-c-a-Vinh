Rest Api

Best practices for REST API design
Accept and respond with JSON
Use nouns instead of verbs in endpoint paths
Name collections with plural nouns
Nesting resources for hierarchical objects
Handle errors gracefully and return standard error codes
Common error HTTP status codes include:
400 Bad Request - This means that client-side input fails validation.
401 Unauthorized - This means the user isn't not authorized to access a resource. It usually returns when the user isn't authenticated.
403 Forbidden - This means the user is authenticated, but it's not allowed to access a resource.
404 Not Found - This indicates that a resource is not found.
500 Internal server error - This is a generic server error. It probably shouldn't be thrown explicitly.
502 Bad Gateway - This indicates an invalid response from an upstream server.
503 Service Unavailable - This indicates that something unexpected happened on server side (It can be anything like server overload, some parts of the system failed, etc.).
Allow filtering, sorting, and pagination
Maintain Good Security Practices
Cache data to improve performance
Versioning our APIs
Conclusion
The most important takeaways for designing high-quality REST APIs is to have consistency by following web standards and conventions. JSON, SSL/TLS, and HTTP status codes are all standard building blocks of the modern web.

Performance is also an important consideration. We can increase it by not returning too much data at once. Also, we can use caching so that we don't have to query for data all the time.

Paths of endpoints should be consistent, we use nouns only since the HTTP methods indicate the action we want to take. Paths of nested resources should come after the path of the parent resource. They should tell us what we’re getting or manipulating without the need to read extra documentation to understand what it’s doing.

Best practices for REST API security: Authentication and authorization
 REST is a simple and flexible way of structuring a web API
 There are three reasons you might find yourself writing a REST API:

To give a networked client that you built—for instance, a single-page app in the browser or on a mobile app on a phone—access to data on your server.
To give end users, both people and programs, programmatic access to data managed by your application.
To let the many services that make up your app's infrastructure communicate with each other.

https://github.com/samayun/devbooks/tree/master js 
https://github.com/dfparker2002/books-2/tree/master  spring
https://github.com/Apress/pro-spring-6/blob/main/chapter03/src/main/java/com/apress/prospring6/three/alias/Award.java code spring

