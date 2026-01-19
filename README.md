
# What is API?

API Stands for Application Programming Interface, it is set of rules or protocols that provides interface \
between two software application to interact with each other and transfer data securely.

API simplifies software programming by enabling developer to integrate data,feature and functionality from other applications,\
instead of building them from scratch. API applications gives simple and secure way to make application data and functionality available to both developers and user clients.

APIs are predefined interfaces that only provide required data for specific requests.\
it doesn`t provide full data, it keeps inetrnal details hidden which helps to maintain system security. 

For example : In Aviation and Logistic related applications instead of developing their own weather forecast they use api to collect required weather data.



# How Actually API Works?
API uses client-server model to exchange data using request and response method.\
THE Application submitting request is called client. server provides the response.

<img src="https://dhtmlx.com/blog/wp-content/uploads/2022/12/how-apis-work-2.png" alt="Alt text" width="800" height="700">

+ A client sends request to an API server through internet. the request is made using specific protocols such as HTTP(hyper text transfer protocol).\the request includes data like request body,http method,endpoint and some parameterto perform operation like retrieving or updating data.
  
    here what http protocol includes
    -  **A request** is sent from client to server.
    -  **An endpoint** defines specific URL path that tells the API what data or action neeeded.
    -  **A method** such as GET(to retrieve data), POST(to send data), PUT(to update) and DELETE specifies the type of request.
    -  **A response** is returned usually in JSON or XML,containing result of the request.
+ The API server receive and process the request. the process may include validation,authorization ,authenticating the client and some other necessary operation.
+ The server sends response back to the client, which includes data ,error message and status code shows the result of the operation.
+ The client receive the response data and process it.

# API Architectural Styles and protocols
API architectures define how systems communicate and exchange data, each offering different levels of flexibility, performance, and structure based on application needs.

* **REST API**: REST is Representational state transfer protocol. It uses HTTPs methods to make request and responses. the request are made through URL paths and response are return in JSON format.
  this is easy to use because of its simplicity, flexibility and statelessness. It is used for public API and web apps.
  
* **SOAP API**: SOAP stands for Simple Object Access Protocol API.It is style that uses and rely strictly on XML protocol to exchange message for request and response. it is widely used in financial related industries like payment Gateways,CRM solutuions.

* **gRPC API**: gRPC is high performance RPC framework, uses protocol buffers rather than JSON or XML as message exchange format for request and response. it is great for microservice architectures.

* **GraphQL API**: It is query langauge allow the clients to ask for specific data as they needed through single path and it eliminates the multiple requests. Client query retrieves needed data only it leads request-response fast and specific.

  # Benefits of API
  API offers wide range of significant benefits to organizations, developer and technology by enabling secure communication between client and server.
  * **Innovation and agility**: API gives data and services as reusable, enables organization and developers to use it and create new feature and application to unlock innovation. API helps to create new methods for fast development instead of building from scratch.
 
  * **Integration and higher performance**: API provides developers and partners data they needed to make it easy for development and fast performance. It can be used by anyone because it shares common syntax to exchange data through HTTPS protocol.
 
  * **Automation**: API automates the repititve work and avoid human errors. it reduces time consuming in work process,allows exceptional user interaction.
 
  * **Security**: API act as security intermediate between client and server by providing only needed data, services and hiding internal system function through interfaces. It provides security in the form of authentication and authorization. they are some kind of authentication like API keys, Bearer token and Oauth etc.
