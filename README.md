# node-docker
- https://docs.docker.com/language/nodejs/build-images/
## How to start the web server ?
```bash
node server.js
```
## How to create messages in the web server ?
```bash
curl --request POST \          
  --url http://localhost:8000/test \
  --header 'content-type: application/json' \
  --data '{"msg": "msg 1", "type": "type1" }'
```
## How to verify the message is created on the web server ?
- http://localhost:8000/test
- You need to install JSON Viewer extension in Chrome to have a nice view of json response 