<p align="center">
  <a href="https://www.docker.com/" target="blank"><img src="https://logopng.com.br/logos/docker-27.png" width="200" alt="Docker Logo" /></a>
</p>

# Build the docker image of the project

```
git clone https://github.com/velfin13/ejemplo-api-nesjs-docker.git
```
```
cd ejemplo-api-nesjs-docker
```

```
docker build -t nest-rest .
```

## To get the project up

```
docker run -d -p 80:3000 --name nodeapp nest-rest
```
