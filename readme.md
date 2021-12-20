## Install Git ##

1. get a github account at github.com

2. install git locally


## Install NodeJs ##

Install following the instructions at the following web page:

```https://nodejs.org/en/download/```

## Cloning a Repository ##

Create a folder for your projects.  Go into that folder.

Inside that college folder, run:

```git clone https://github.com/Aditi369/Blockchain2021.git```

## Updating Code in Repo from Github ##

From the terminal in Visual Studio Code (or from the command line - as long as you are in the folder), run the following command:

```git pull origin main```

## for the moment ##

you need git, nodejs and vs code installed.

## Validation Steps ##


```$git version```

```$node -v```

## Using your own repo ##

First, create a repo in github.

git clone into a folder

make your changes

then run the following commands:

```$git add .```

```$git commit -m "Adding code to Repository"```

```$git push origin main```

## Executing a .JS file ##


```$node contract.js```
```$node distribute.js```

## Dependencies and NPM ##


From inside your folder, to create your own package.json:

```$npm init```




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
