# Sample application demonstrating how to use [Spring REST Docs](http://docs.spring.io/spring-restdocs/docs/current/reference/html5/) with TestNG for documenting RESTful APIs

 _Document RESTful services by combining hand-written documentation with auto-generated snippets produced with Spring MVC Test._

## In any project 

 * *Having no documentation is better than having wrong documentation.*
 * *Documentation should be easy to write, in a format which is designed for writing.*
 * *Framework should not be analyzing your implementation to predict documentation.*


## Benefits:
* *Easy to package the documentation in your project jar’s file.*
* *Snippets for : Hypermedia links, Request and response payloads, Request parameters, Path parameters and HTTP headers.*
* *Easy to customize the response or request before it is documented.*
* *Easy to add extra information to the snippets.*
* *Easy to ignore parts of the request or response during documentation.*
* *Easy to make parts of the request or response as optional.*
* *Support for both JSON and XML.*
* *Support coming for rest assured.*
* *Ideal for brown field stubbing.*

## Running the project

* Build the project:

```
./gradlew clean build
```

* Snippet Location:
```
build/generated-snippets/sample/
```

* REST API documentation
```
build/asciidoc/html5/
```