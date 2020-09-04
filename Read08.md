# Express Routing 

### Routing
- Routing refers to how an application’s endpoints (URIs) respond to client requests.

- You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests.
For a full list,You can also use app.all() to handle all HTTP methods and app.use() to specify middleware as the callback function.

### Route paths
Route paths, in combination with a request method, define the endpoints at which requests can be made.

### Express 4.0
Express 4.0 comes with the new Router.Router is like a mini express application. 
It doesn't bring in views or settings, but provides us with the routing APIs like .use, .get, .param, and route.
