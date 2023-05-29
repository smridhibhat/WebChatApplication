## Global node js packages

$ npm install -g ts-node@10.5.0
$ npm install -g nodemon
$ npm install -g db-migrate
$ npm install -g db-migrate-pg


## Important
Before starting, install docker-compose to your machine and start docker containers:
```bash
$ docker-compose up
```

## Environment
* need create .env file
* example: .env.sample

## Migrate database
```bash
# Create tables
$ npm run up
# Delete tables
$ npm run down
```

## Start project
```bash
$ npm install
$ npm run start:dev
```
