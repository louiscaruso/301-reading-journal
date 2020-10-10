# Heroku Deployment
 - First we could create a server and call it server.js
  ```
  var http = require("http");

  http.createServer(function(request, response) {
    response.writeHead(200, {"Content-Type": "text/plain"});
    response.write("It's alive!");
    response.end();
  }).listen(3000);```

- In the terminal run `node server.js`
- Log into heroku from computer
- Create a json file
  ```
  {
  "name" : "blog",
  "version" : "0.0.1",
  "description" : "My minimalistic blog",
  "dependencies" : {
    "mime" : "~1.2.7"
  }
}```
