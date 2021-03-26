
[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-02
### The PUT method
- The PUT method is most often used to update an existing resource. If you want to update a specific resource (which comes with a specific URI), you can call the PUT method to that resource URI with the request body containing the complete new version of the resource you are trying to update.
 ### The PATCH method
- The PATCH method is very similar to the PUT method because it also modifies an existing resource. The difference is that for the PUT method, the request body contains the complete new version, whereas for the PATCH method, the request body only needs to contain the specific changes to the resource, specifically a set of instructions describing how that resource should be changed, and the API service will create a new version according to that instruction. attribution : https://medium.com/@9cv9official/what-are-get-post-put-patch-delete-a-walkthrough-with-javascripts-fetch-api-17be31755d28 )
 ### SOAP Vs. REST: Difference between Web API Services
- SOAP is a protocol which was designed before REST and came into the picture. The main idea behind designing SOAP was to ensure that programs built on different platforms and programming languages could exchange data in an easy manner. SOAP stands for Simple Object Access Protocol.

- REST was designed specifically for working with components such as media components, files, or even objects on a particular hardware device. Any web service that is defined on the principles of REST can be called a Restful web service. A Restful service would use the normal HTTP verbs of GET, POST, PUT and DELETE for working with the required components. REST stands for Representational State Transfer.

### KEY DIFFERENCE

- SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State Transfer.
- SOAP is a protocol whereas REST is an architectural pattern.
- SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the components on the hardware device.
- SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.
- SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.
- SOAP cannot make use of REST whereas REST can make use of SOAP.
 ### Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
- https://www.npmjs.com/package/mockserver 

- https://learning.postman.com/ 

- https://stoplight.io/mocking/ 

- https://swagger.io/tools/swagger-inspector/ 

- source : https://nordicapis.com/10-tools-to-mock-http-requests/ 

- A mock API server or mock server API imitates a real API server by providing realistic mock API responses to requests. They can be on your local machine or the public Internet. Responses can be static or dynamic, and simulate the data the real API would return, matching the schema with data types, objects, and arrays.

- Swagger Simplify API development for users, teams, and enterprises with the Swagger open source and professional toolset. Find out how Swagger can help you design and document your APIs at scale.

### apidoc vs swagger for node app

- Popularity: By comparing stats, swagger-ui is more popular then apidocjs.

- Consistency: If we already using swagger for our Dotnetcore service, then implementing swagger tool will consist more from Info and UI prospective.

- Implementation complexity: apidocjs and swagger both required documentation content on implemented method as customize comment data. In addition they allow to write documentation data in separate resource file as .js and .json. If we already have swagger. Son created by DotnetCore we can reuse more than 80% specification.

- Maintenance: For apidocjs will have to modify documentation for each affected method/endpoints if service changed. In swagger we can limit changes. But by implementing apidocjs we can isolate the layer.

- Other benefits: Because swagger use plain .json that could be parsed through programing language, thus we can get advantage of various other 3rd parties in order to create http client and more.

- Future: Due to popularity of swagger, apidocjs provide information about apidoc-swagger converter so we can switch apidoc to swagger anytime.

source:https://www.asptricks.net/ )

### Document the following Vocabulary Terms Term

- Web Server

- Express

- Routing

- WRRC