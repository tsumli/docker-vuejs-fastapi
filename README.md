# docker-vuejs-fastapi
An example of Vue.js and Fastapi using Docker (docker-compose).

1. Clone this repo and build docker images.
```sh
git clone https://github.com/tsumli/docker-vuejs-fastapi.git
cd ./docker-vuejs-fastapi
docker-compose build
```

2. Create containers to start frontend/backend servers.
```sh
docker-compose up
```

3. Access to the browser (Defaults to http://localhost:3000).
