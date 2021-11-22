# Data Sending Application
This application used a very basic one-way Client and Server setup where a Client connects, sends messages to server and the server shows them using socket connection.

## Server

The command that should be done to get into the container shell instead of running the applications by default 
```
docker run -it --network javaserver3 --mount source=servervol,target=/usr/src/app/serverdata serverjava:1.0 /bin/bash
```
## Client

The command that should be done to get into the container shell instead of running the applications by default 
```
docker run -it --network javaserver3 --mount source=clientvol,target=/usr/src/app/clientdata clientjava:1.0 /bin/bash
```
## How to run this Project

For this you will find two shell scripts inside this project i.e. **fileclient.sh** and **fileserver.sh**. Firstly run the fileserver.sh and then you have to run fileclient.sh. You have to run these two files and you are ready to go.

