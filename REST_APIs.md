# REST APIs

## What is REST API
**[Architecture]**
* 1-tier architecture
*  2-tier architecture client server
*  3-tier architecture client server database(storage)
How the communication should happen is API. 
Popular way REST API -Representational State Transfer Application programming interface
HTTP - Hyper text transfer protocol - how to communicate the structure
## Why REST API 
* Ease of Use
* Stateless -> server doesn't know the previous info when it sees api. like chef doesn't know table no. looking at waiter
* Scalability
* Flexibility with data
* Uniform interface
* Caching
* Separation of concerns
* Interoperability -language agnostic
* Ease of testing
* Security

## Building Blocks of REST
[dummyjson](https://dummyjson.com/docs/todos)
* ![req res](https://codingnomads.com/images/afe3a1ed-36ca-4340-dcd5-4882aa364c00/public)
* 
![](https://www3.ntu.edu.sg/home/ehchua/programming/webprogramming/images/HTTP_ResponseMessageExample.png)

## Build app 

### URL
![URL](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVS6xIl35kcxWTg-UuAlogJQ4q7yfZYUGFuw&s)

### Methods
FOR CRUD - 
* POST, GET, PUT/PATCH, DELETE, HEAD, OPTIONS
* OPTIONS - Say if you are making a request from one server to another asking if you are allowed or not
* CONNECT - to establish the connection
* TRACE - trace used to diagnose request and response used in production

### Headers
**Request Headers**
![2025 2](https://github.com/user-attachments/assets/3cabd24e-9f72-4779-89e1-9cd383abf885)
![2025](https://github.com/user-attachments/assets/379a12ef-9d83-4e94-b985-f3a4fdde5f47)

**Response Headers**
![2025 2](https://github.com/user-attachments/assets/f9e000a5-982b-4b7f-8c52-0bd8f767f776)
![2025 3](https://github.com/user-attachments/assets/493e2d8e-b87d-4210-ba60-9dce7295eaa1)

### Request
![2025](https://github.com/user-attachments/assets/83c34f96-f31a-4007-8d78-6587f8c0cd7e)
### Response
### Status code
* Status Range : Use Case : Status code : Example
*> 1XX - Information related - 
* > 100 - continue
* > 101 - continue 

*> 2XX - Success - 
* > 200 Ok
* > 201 Created
* > 202 Accepted
* > 204 No Content
* > 206 Partial Content (Small chunks are coming while downloading)

*> 3XX - Redirection -
* > 301 Moved Permanently
* > 302 Temporary Moving
* > 307 ~ 302 =  Retain method
* > 308 ~ 301 =  Retain method
 
*> 4XX - Client Error - 
* > 400 Bad request
* > 401 Unauthorized
* > 403 Authorization
* > 404 Not Found
* > 405 Method not allowed
* > 429 Concurrent request

*> 5XX - Server Error -
*> 500 Internal server error
* > 502 Bad Gateway
* > 503 Services unavailable
* > 504 Gateway Timeout
* > 507 Insufficient Storage

## Postman
## http1/2/3
## Best practices
## Advance

