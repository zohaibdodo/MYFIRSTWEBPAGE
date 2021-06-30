# To containerize this app, follow these steps

docker build -t first-docker-app .

docker container run --name=first-docker-cont -d -p 8500:80 first-docker-app

# That's it!!! now click on following

http://localhost:8500