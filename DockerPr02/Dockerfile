
FROM ubuntu:latest
COPY . /usr/src/docker1
WORKDIR /usr/src/docker1
RUN apt update
RUN apt install -y g++ nano
RUN g++ -o DockerPr02 main.cpp
CMD ["./DockerPr02"]