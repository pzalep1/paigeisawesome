# :coffee: Curricular Coffee Development Environment
Curricular Coffee is a MERN stack application built to help educators create
quality curriculum. 

## How to Use Me
There are three elements to this environment: 

1. Mongo Database running in Docker
2. coffee-service acting as our backend application
3. curricular-client acting as our frontend application

```sh
$ cd cosc617
$ git submodule init
$ git submodule update
```
### Running the Database

```sh
$ docker-compose up
```
### Running the Backend Application

```sh
$ cd coffee-service
$ npm start
```

### Running the Frontend Application 

```sh
$ cd curricular-client
$ npm run start
```

