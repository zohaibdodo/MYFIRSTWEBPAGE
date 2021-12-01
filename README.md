# MYFIRSTWEBPAGE

This repo contain basic web application folders to use for practicing Dockers for containerizing app

Follow the following steps
If you don't have git installed on your system, follow the following steps in Terminal/Shell
```
sudo apt-get update
```
```
sudo apt-get upgrade
```
```
sudo apt-get install git
```
Once you have installed Git, follow the following steps
```
git clone https://github.com/zohaibdodo/MYFIRSTWEBAGE.git
```
```
ls
cd MYFIRSTWEBPAGE/
ls
```
Now you can see that different folder have been cloned on your system, go to any folder and follow instruction from README file inside each folder

## To containerize this app, follow these steps

```
docker build -t first-docker-app .
```
```
docker container run --name=first-docker-cont -d -p 8500:80 first-docker-app
```

## That's it!!! now click on following

http://localhost:8500