const http = require('http');

const port = 3000;

const server = http.createServer ((req,resp) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello World');
});

server.listen(port, () => {
  console.log(`Server running on port: $(port)`);
});
