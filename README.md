# Reverse proxy example
using docker-compose and nginx image

## Prerequisite
- node.js
- docker-compose
- no service running on localhost ports 80, 3000, 5000

## Start
```sh
# install dependencies
npm i

# serve ports 3000 and 5000, and container with nginx image
npm start
```

Open browser at http://localhost and navigate to http://localhost:* using http://localhost/*