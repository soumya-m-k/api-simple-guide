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
    -  **request** is sent from client to server.  
+ The API server receive and process the request. the process may include validation,authorization ,authenticating the client and some other necessary operation.
+ The server sends response back to the client, which includes data ,error message and status code shows the result of the operation.
+ The client receive the response data and process it.
