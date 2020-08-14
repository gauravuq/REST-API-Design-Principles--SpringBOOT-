# REST Service Design Principles:
* **Uniform interface for accessing resources.**
	* **hi**
* **Client and Server should be able to evolve separately without any dependence on each other. A client should know only resource URIs, and that’s all.**
* **No client context shall be stored on the server between requests. The client is responsible for managing the state of the application.**
* **Well-managed caching partially or completely eliminates some client-server interactions, further improving scalability and performance.**
* **Layered Architecture: one server for authentication, one server for storage etc. Client is should not be able to tell if it is connected to an intermediary or not**
* **Code on demand: You are free to return executable code to support a part of your client's application**

## Sample Spring REST Service Following REST Constraints
### Travel Api serving resources
* ****
