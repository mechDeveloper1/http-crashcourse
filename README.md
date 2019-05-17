# http-crashcourse
http:// Crash Course

> Credits: Traversy Media |
> YouTube Link [here](https://www.youtube.com/watch?v=iYM2zFP3Zn0)

### What is HTTP?
- **H**yper **T**ext **T**ransfer **P**rotocol
- Communication between web servers & clients
- HTTP Requests / Responses
- Loading pages, form submit, Ajax calls

### HTTP is Stateless
- Every request is completely independant
- Similar to transactions, each http request is single transaction, previous transactions are not remembered
- Programming, Local Storage, Cookies, Sessions are used to create enhanced user experiences

### What is HTTPS?
- **H**yper **T**ext **T**ransfer **P**rotocol **S**ecure
- Data sent is encrypted
- SSL/TLS
- Install certifcate on web host

### HTTP Methods
- GET
  Retrieves data from server (visitng a web page, loading a standard HTML page loading assets like CSS, Images, JSON Data, XML Data etc )
- POST
  Submit data to the server (submitting a form, sending data to the server)
- PUT
  Update data already on the server
- DELETE
  Deletes data from the server
- Above are most widely used basic HTTP methods there are couple of more HTTP Methods

### HTTP Header Fields
With each request and response with HTTP you have something called header and something called the body

General: | Response: | Request:
-------- | --------- | --------
Request URL | Server | Cookies
Request Method | Set-Cookie | Accept-xxx
Status Code | Content-Type | Content-Type
Remote Address | Content-Length | Content-Length
Referrer Policy | Date | Authorization
 |  |  | User-Agent
 |  |  | Referrer
 
 
 ### HTTP Status Codes
 
 ###### 100 to 500 Range
 - 1xx : Informational
 - 2xx : Success
 - 3xx : Redirect
 - 4xx : Client Error
 - 5xx : Server Error

  ###### Most common HTTP Status Codes
   - 200 - OK
   - 201 - OK Created
   - 301 - Moved to new URL
   - 304 - Not Modified (Cached version)
   - 400 - Bad request
   - 401 - Unauthorized
   - 404 - Not found
   - 500 - Internal server error
