--Docker Cheat Sheet--

Command to get the currently installed version of docker:

`:~ $ docker --version
Docker version 20.10.8, build 3967b7d`

Command to display docker version with formatting:

`:~ $ docker version --format '{{.Server.Version}}'
20.10.8`

To pull images from docker (ubuntu):

`:~ $ docker pull ubuntu
Using default tag: latest
latest: Pulling from library/ubuntu
2ab09b027e7f: Pull complete 
Digest: sha256:67211c14fa74f070d27cc59d69a7fa9aeff8e28ea118ef3babc295a0428a6d21
Status: Downloaded newer image for ubuntu:latest
docker.io/library/ubuntu:latest`

To create a container from an image:

`:~ $ docker run -it -d ubuntu
a22398343bc21f8b16f17181edee3ebe15c561eb436412f0a3e51bcc49262e4c`

To list the running containers:

`:~ $ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES`











