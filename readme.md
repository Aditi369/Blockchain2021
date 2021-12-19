
## Docker ##

### View running docker containers ###

```docker ps```

### build a docker container ###

```docker build -t nci/lab2021 .```

### run the image ###

```docker run -p 8090:8080 --name nci -d nci/lab2021```

### kill a running container ###
```docker kill [name]```

### start/stop a container ###
```docker start/stop [name]```

### view logs ###
```docker logs [name]```

### view logs inside a container ###
```docker logs -f [name]```

### view images on your computer ###
```docker image ls```

### clear the docker system ###
```docker system prune -f```

### remove all docker images ###
```docker image prune -a -f```

### run docker-compose ###
```docker-compose up```

to run it in detached mode:

```docker-compose up -d```


## Requirements for Assignment ##

### 1. create an ethereum account ###
This is completed inside metamask (12 words, create an account, fund with Ropsten ether)

### 2. Create an ERC20-compliant, fixed-supply token
using open zeppelin contract, 

### 3. Deply to Ropsten
deploying using injected web3 and metamask


