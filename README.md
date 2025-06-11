# simple flask docker example
super simple example of docker with a flask app

# how to run
how to run this project

## Cloning the repo 
first to run this example we need to clone the project
```bash
git clone https://github.com/StickyCoolDev/docker-flask-example
```
and change the directory to the cloned repo

```bash
cd docker-flask-example
```

## Building the **Container**

to build the container we need to use the docker build command
```bash
# by using the . (current) directory we are telling
# docker to look for a Dockerfile in the current directory
docker build -t cool-app . 
```
## Running the **Container**

after building the container we need to run it with the docker run command
```bash
docker run -p 5000:5000 cool-app # running the container with port 5000 mapped to 5000
```
