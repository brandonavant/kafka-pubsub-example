# kafka-pubsub-example

Demonstrates how to publish and subscribe to a Kafka topic.

## Running the example

The sections below describe what is necessary to get this example up and running.

### Setting Up Kafka

To run the example, you will need to first setup your Kafka cluster. This step is outside of the scope of this example. To read more about ways to do this, please consider one of the documentation sources below:

- [Confluent Cloud](https://www.confluent.io/confluent-cloud/tryfree)
- [Manual Install](https://kafka.apache.org/quickstart)

### Running Via Docker

This example is intended to run in docker using _docker-compose_. To do this, you will need to first [install Docker]() and then [Docker Compose](). Once these are installed, you can start up the process by running the following command **at the same level as the docker-compose.yml**:

```bash
docker-compose up
```

This will install the necessary images, build them, and start up the two applications.

### Running Manually



