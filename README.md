# Fabric-Setup
The best source of information on fabric setup is [THIS WEBSITE](https://hyperledger-fabric.readthedocs.io). If any of the instruction below does not work, fall back to the main fabric doc.

Fabric is easiest run on an UNIX like environment. Preferably Ubuntu 16.04 and MacOS. 
It can work in a windows environment. But it requires extra steps and I won’t be covering that in this.


## **Docker and Docker Compose**

Version 17.06.2 or greater is required. 

For Mac - https://docs.docker.com/docker-for-mac/install/

For Linux - (ubuntu) https://docs.docker.com/install/linux/docker-ce/ubuntu/ 

      (You can find other distros there as well)


## **Go Programming Language**

Install Go https://golang.org/doc/install

And set go in your path. 

**Alternative Install:**
MacOS users can use [brew](https://brew.sh/) as well https://ahmadawais.com/install-go-lang-on-macos-with-homebrew/
Ubuntu users can use apt-get https://github.com/golang/go/wiki/Ubuntu



## **Node.js Runtime and NPM**

*Node.js version 9.x is not supported at this time.*

- [*Node.js*](https://nodejs.org/en/download/) *- version 8.9.x or greater*


**Alternative Install:**
If you want to have multiple versions of node installed in the system nvm is great. 
https://github.com/creationix/nvm


## **Python**

Node needs python 2.7 to be installed. 

You can make use of virtual env for this if the default python is 3.6


## Get The Starter Code
    ```curl -sSL http://bit.ly/2ysbOFE | bash -s 1.2.1```

Run the above command in the directory you want to download the sample codes in. 
This will also download the docker images.

