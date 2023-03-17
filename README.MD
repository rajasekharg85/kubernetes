###### Docker file

Dokerfile is a declarative way of creating our own images, Docker will give us some syntax to create our own images.

File name should be Dockerfile. docker command should run where your Dockerfile exists

#### How to build image from Dockerfile

'''''

docker build -t [docker-hub-URL]/[your-username]/[imagename]:version.

#### How to push image to Dockerhub

docker push [docker-hub-URL]/[your-username]/[imagename]:version.