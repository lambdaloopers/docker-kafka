# Lambdaloopers Kafka

Kafka Queue implementation with Zookeeper group management.

https://www.slideshare.net/lambdaloopers/kafka-infrastructure-development
https://www.slideshare.net/lambdaloopers/kafka-infrastructure-production
https://www.slideshare.net/lambdaloopers/kafka-infrastructure-services
https://www.slideshare.net/lambdaloopers/kafka-infrastructure-monitoring
https://www.slideshare.net/lambdaloopers/kafka-infrastructure-cloud

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

In order to run this application, you need to install
docker and docker-compose on your development environment.

How to setup the development environment:

* [Docker Engine](https://docs.docker.com/engine/installation/) - Guide to install docker on multiple environments.
* [Docker Compose](https://docs.docker.com/compose/install/) - Guide to install docker-compose on multiple environments.


### Installing

First you'll need to set a `.env` for the host IP of the kafka,
run `cp .env.example .env` in the root directory of the application 
and change the values to the desired ones.
After that simply run `./bin/start.sh` and your kafka will be listening in the fixed IP on port 9092 by default.


## Built With

* [Apache Kafka](https://kafka.apache.org/) - A distributed streaming platform
* [Apache Zookeeper](https://zookeeper.apache.org/) - centralized service for highly reliable distributed coordination


## Authors

* **LambdaLoopers S. L.** - *Isolation of kafka and Zookeeper services* - [site](https://lambdaloopers.com)
