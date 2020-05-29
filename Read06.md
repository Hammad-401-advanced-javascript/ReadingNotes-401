# HTTP and REST
## (HTTP) is a stateless request-response application layer protocol.
**The HTTP specification defines how requests and responses should be formatted, but not what a service should represent.**

### HTTP Request 
**A HTTP/1.1 request is formatted in text and transferred using TCP. The first line of the request contains the METHOD, URL, and HTTP VERSION.**

#### Safe :
**methods should only be used for information retrieval and should not change the server state.**
#### Idempotent :
**methods means if two identical requests are made they should get an identical response.**
#### Cacheable :
**means the client should be able to cache the response.**

### HTTP Response :
**A HTTP/1.1 response is also formatted in text and transferred using TCP. The first line of the response contains the HTTP VERSION, STATUS CODE, and STATUS MESSAGE.**

## REST :
**REST is acronym for REpresentational State Transfer. In layman’s terms, is a means by which we can reference, manipulate, and transfer state.**

![image](http://safehammad.com/wp-uploads/2010/10/json-rest3.png)
