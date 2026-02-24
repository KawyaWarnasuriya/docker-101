FROM node:18-alpine

WORKDIR /app

RUN echo "const http = require('http'); \
http.createServer((req,res)=>{res.end('API Working');}).listen(3000);" > server.js

EXPOSE 3000

CMD ["node", "server.js"]