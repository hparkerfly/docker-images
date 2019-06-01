# kafka-quickstart
This image is meant to be a minimal container running Apache Kafka

## Installing Docker

    https://download.docker.com/linux/ubuntu/dists/xenial/pool/stable/amd64/

## Avoid permission issues

##### Add current user to docker group
    sudo usermod -aG docker $USER
##### Change the permissions of docker socket to be able to connect to the docker daemon
    sudo chmod 666 /var/run/docker.sock

## Building Image

    docker build -t kafka-quickstart:2.2.0 .

## Create and Run Container  
    
    docker run --name kafka -d kafka-quickstart:2.2.0z

## Documentation
General Kafka Documentation: https://kafka.apache.org/
