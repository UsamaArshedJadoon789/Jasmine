# Platform Setup Guide

## Environment Setup
- Java 11 OpenJDK
- Environment variables configured in platform_configs/env.sh

## Kafka Setup
- Version: 3.5.1
- ZooKeeper running on port 2181
- Kafka broker running on port 9092

## Flink Setup
- Version: 1.18.1
- JobManager and TaskManager configured
- Checkpoints directory: /home/ubuntu/Jasmine/flink/checkpoints

## Configuration Files
- Kafka: kafka/config/server.properties
- Flink: flink/conf/flink-conf.yaml
