# Typescript Backend Template
  
## Overview
This project is a backend typescript template done by me.

Here you will find a quick-start solid project structure to start coding.

In this project I'm using docker-compose to keep the app up, express and Postgres Database, also included in the docker-compose script.

To adjust into your needs, you will need to edit the "docker-compose" file with the desired database and container name, for the app

You will need to change the configs inside "ormconfig.example.json" as well, and create the "ormconfig.json" file, instead of example.

You would like to edit the first configs inside package.json as well, since it have some templating data.

The project includes configurations for API docs with swagger, you can access it in http://localhost:3333/api_docs. I've created a simple GET Ping route, to guarantee its execution. You can edit your documentation in the "swagger.json" file, located at "src/".

The project also includes eslint, prettier and editorconfig configurations, since I like using it.

## Installation & Running
First of all, you will need nodeJS and docker in their latest versions.

You will need to install the project dependencies, with:
```shell
yarn OR npm install
```

The app is shipped with docker, so running our docker-compose script will install the project Database and keep it running until downed.
To install docker compose, run:
```shell
docker-compose up -d
```

After the docker-compose execution, the project will be running at: **http://localhost:3333**
Make sure that this port is available

## Contact
**Email: regisprogramming@gmail.com**
[LinkedIn](https://www.linkedin.com/in/regissfaria/)
[GitHub](https://github.com/regisfaria)
[GitLab](https://gitlab.com/regisfaria)
