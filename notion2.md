$ npm install prerender
const prerender = require('prerender');
const server = prerender();
server.start();
curl http://localhost:3000/render?url=https://www.example.com/
