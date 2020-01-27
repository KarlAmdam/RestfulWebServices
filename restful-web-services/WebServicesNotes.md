Service provider, and consumer

Service privder is the one that gives information 
Consumer is the one who takes information from the service provider.


Service definition is the contract of the request and response.

Endpoint is the URL that the service expose to the consumer.




Transport defines how a service is called.
popular formats is HTTP and MQ.
A service that is exposed over a service queue. 




Groups of web services

SOAP - Simple Object Acess Protocol
- Use XML as the request exchange format
- Soap defines a specific XML response and request method. You have to use an Envelope for this. 

REST - Representational State Transfer
- Want to make best use of HTTP
- Uses a combination of HTTP Methods (GET, PUT, POST, etc..) and responds with Status Codes (200, 404, 500 etc..)
- A recource has an URI (Uniform Resource Identifier)
    - Example: /user/Karl

- Define your Recource and perform a Method on this recource. 
- Think in therms of recources. What do you want to expose to the different applications?
- No restriction in REST. Can use JSON.
- Transport: Only HTTP.
- Service Definition: No standard, alternatives are WADL and Swagger

REST and SOAP differences
- SOAP always contain XML, REST has no strickt data exchange. 
- JSON is most popular deta exchange in REST.
- SOAP does not have any Transport restriction, REST only uses HTTP.
- RESTfull services typically easier than SOAP to implement. 

