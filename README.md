# docker react sass

## Required Node Version


## Docker cmd

```
// build
docker build -t my-react-app:latest .

// run 3000 port with background
docker run -d -p 3000:3000 my-react-app:latest

// access docker container
docker run -it my-react-app:latest /bin/bash

// stop all local docker
docker stop $(docker ps -q)
```