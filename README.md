# Microservices Blog
An over compilcated blog to show case some microservices concepts 😅

## Technologies used
- Node.js
- gRPC
- GraphQL
- Docker
- Docker-Compose

## Architecture
![](https://www.lucidchart.com/publicSegments/view/27db3963-5db1-459a-a55c-c941aa00280d/image.png)

## Services
All the services can be found in the `srv` folder.
- frontend
- gateway
- auth
- users
- articles
- comments

## How to run this? 🤔
There multiple options on how the application, but for local development we are going to use `docker` and `docker-compose`.
```shell
$ npm run compose
```