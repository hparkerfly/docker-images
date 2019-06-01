# kafka-quickstart
This image is meant to be a minimal container running Apache Kafka

## Installing Docker

    https://download.docker.com/linux/ubuntu/dists/xenial/pool/stable/amd64/

## Building Image

    docker build -t kafka-quickstart:0.10.2.0 .

## Create and Run Container  
    
    docker run --name kafka-quickstart -d kafka-quickstart:0.10.2.0

## Documentation
General Kafka Documentation: https://kafka.apache.org/
