# MYFIRSTWEBPAGE

This repo contain basic web application folders to use for practicing Dockers for containerizing app

Follow the following steps
If you don't have git installed on your system, follow the following steps in Terminal/Shell
```
sudo apt-get update
```
```
sudo apt-get upgrade -y
```
```
sudo apt-get install git
```
Once you have installed Git, follow the following steps
```
git clone https://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@github.com/zohaibdodo/MYFIRSTWEBPAGE.git

```
```
ls
cd MYFIRSTWEBPAGE/
ls
```
Now you can see that different folder have been cloned on your system, go to any folder and follow instruction from README file inside each folder

## To containerize this app, follow these steps

```
docker build -t myfirstwebpage .
```
```
docker container run --name=myfirstwebpage -d -p 8500:80 myfirstwebpage
```

## That's it!!! now click on following

http://localhost:8500