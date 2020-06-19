To run this project on docker image, copy it in your local repo.

`git clone https://github.com/kumarsiddy/angular-docker.git`

`cd angular-docker/`

run this command to create the image

`docker build -t hello-world-image .`

check if docker image has been created

`docker image ls`

run the creaed docker image and open the port

`docker run --name hello-world-container -d -p 8080:80 hello-world-image`

to check go to `http://localhost:8080`
