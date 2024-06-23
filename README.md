# ETL Data Pipeline: RDBMS to HDFS Using Airflow DAG

이 프로젝트는 Apache Airflow와 Spark를 사용하여 MariaDB에서 데이터를 추출하고 이를 Hadoop HDFS에 CSV 파일로 저장하는 DAG를 구축합니다.

## :bookmark_tabs: Contents

- [Table of Contents](#table-of-contents)
- [About](#about)
- [Features](#Features)
- [Prerequisites](#Prerequisites)
- [Installation](#installation)


```bash
dags
├── plugins
│   └── slack.py
│   └── teams.py
│   rdbToHadopp.py
└── spark_submit.py
```

## Features
- run kafak using docker
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
