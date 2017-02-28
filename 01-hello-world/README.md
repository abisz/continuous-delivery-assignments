# Hello World

To get the hello-world app running follow these steps:
```
# build the Docker image
sudo docker build -t cda/hello-world .

# run container
sudo docker run -p 8080:3000 --name helloworld cda/hello-world
```
The app should now be available at (http://localhost:8080);
