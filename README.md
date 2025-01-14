# Developing a Single Page App with FastAPI and Vue.js

### Want to learn how to build this?

Check out the [post](https://testdriven.io/blog/developing-a-single-page-app-with-fastapi-and-vuejs).

## Want to use this project?

Build the images and spin up the containers:

```sh
/usr/bin/docker-compose -f docker-compose.yml -p fastapi-vue up -d
```

Apply the migrations:

```sh
/usr/bin/docker-compose exec backend aerich upgrade
```

Stop containers

```sh
/usr/bin/docker-compose -f docker-compose.yml -p fastapi-vue stop backend frontend db
```


Ensure [http://localhost:5000](http://localhost:5000),
[http://localhost:5000/docs](http://localhost:5000/docs), 
and [http://localhost:8080](http://localhost:8080) work as expected.
