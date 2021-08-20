Start project
========================
```
# Build containers
$ docker-compose build

# start project
$ docker-compose up

```

##Using list of environment variables
 ####At backend folder you can find .env file:

```
 DB_NAME='TodoDB' // name of table on db
 DB_LOGIN='postgres' // login of connecting to db
 DB_PASSWORD='123' // password of connecting to db
 DB_HOST='db' // host of db
 DIALECT='postgres' // setting dialict for connecting to db from Sequlize
 NODE_ENV='production' // mode of working with db 
```
####At frontend folder you also can find .env file:
```
BASE_URL='http://localhost:3001/'
```
BASE_URL - it's url for requests to backend 

