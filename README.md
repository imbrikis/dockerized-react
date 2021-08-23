# A basic React app that has been Dockerized

- Just me trying to understand how to Dockerize applications

### To run (make sure Docker Desktop is running):

```
npm install
docker build -t imbrikis/simple-react-app .
docker run -d -it -p3000:3000 --name simple-react-app imbrikis/simple-react-app
```

[Or download the Docker image](https://hub.docker.com/repository/docker/imbrikis/simple-react-app)
