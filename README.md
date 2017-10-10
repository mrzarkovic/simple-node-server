# Example server

```
var http = require("http");

var server = http.createServer(function(request, response) {
  response.writeHead(200, {"Content-Type": "text/html"});
  response.write("Hello World!");
  response.end();
});

server.listen(3000);
console.log("Server is listening on port 3000");
```

# Start server
Run `node index` and visit localhost:3000