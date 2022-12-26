docker build -t sample-original -f Dockerfile-original .

docker image ls | grep sample

docker build -t sample-multistage -f Dockerfile-multistage .


# Java

docker build -f Dockerfile-original -t java-original .


docker build -f Dockerfile-distroless -t java-distroless .