# Kafka

Connect to Apache Kafka and create a producer and consumer using Python

## Features
- run Kafak using docker-compose
- create kafak topic
- create kafka producer & consumer using python

## Prerequisites
- Python 3.9
- kafka-python==2.0.2

## Installation

Provide instructions on how to install or set up your project. Include any dependencies or prerequisites needed.

Install kafka usiing docker-compose
```bash
$ docker-compose up -d 
```

Install Kafka and Python client
```bash
$ pip install kafka-python
```

Run the producer script to send messages to the my_topic.
```bash
$ python producer.py
```

Run the consumer script to read messages from the my_topic.
```bash
$ python consumer.py
```
