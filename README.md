# IIEC_RISE Docker Project under the mentorship of Vimal Daga Sir .


## Docker Nodejs Vue Todo list example
#Pradeep Kumar
> Project of a docker in Node/Vue/Mongo app

## Prerequistes to base machine install below package
> Install npm yet node.js file execute
## Quick Start

First you need to create a .env file in the frontend directory and add a variable.

```bash
VUE_APP_API_URL=http://localhost:3000
```

Start the application

```bash
# Run in Docker
docker-compose -f docker-compose.yml up
# use -d flag to run in background

# Tear down
docker-compose down

# To re-build
docker-compose build
```
