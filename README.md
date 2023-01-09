<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

<p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>

<p align="center">
<a href="https://www.docker.com/" target="_blank"><img src="https://img.shields.io/badge/docker%20build-ok-blue" alt="Docker build" /></a>
<a href="https://www.mongodb.com/" target="_blank"><img src="https://img.shields.io/badge/database-mongodb-green" alt="Database MongoDB" /></a>
</p>

## Description

Basic CRUD made with [Nest](https://github.com/nestjs/nest) framework TypeScript starter repository using MongoDB as the database.

<br>

## Installation
You need to have docker installed to run this project.

```bash
$ docker-compose up
```

<br>

## Available Routes
You can test the project routes using one of the options bellow:

<br>

### GET: (Search Users)
> http://localhost:3000/users/

<br>

### GET: (Find One)
> http://localhost:3000/users/{{user-id}}

<br>

### POST: (Create User)
> http://localhost:3000/users/
```json
{
	"email": "test@test.com",
	"name": "User Test",
	"password": "1234"
}
```

<br>

### PATCH: (Update User)
> http://localhost:3000/users/
```json
{
	"email": "test@test.com",
	"name": "User Test",
	"password": "1234"
}
```

<br>

### Delete: (Delete User)
> http://localhost:3000/users/{{user-id}}

<br>

## License
Nest is [MIT licensed](LICENSE).
