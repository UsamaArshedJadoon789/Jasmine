# Platform Configurations

## Hadoop (3.3.6)
- **Installation Directory**: `/opt/hadoop`
- **Configuration Files**: 
  - `/opt/hadoop/etc/hadoop/core-site.xml`
  - `/opt/hadoop/etc/hadoop/hdfs-site.xml`
  - `/opt/hadoop/etc/hadoop/hadoop-env.sh`
- **Data Directories**:
  - NameNode: `/opt/hadoop/data/namenode`
  - DataNode: `/opt/hadoop/data/datanode`
- **Environment Variables**:
  ```bash
  export HADOOP_HOME=/opt/hadoop
  export HADOOP_CONF_DIR=/opt/hadoop/etc/hadoop
  export PATH=$PATH:$HADOOP_HOME/bin:$HADOOP_HOME/sbin
  ```

## Spark (3.4.1)
- **Installation Directory**: `/home/ubuntu/Jasmine/spark`
- **Configuration Files**:
  - `spark/conf/spark-env.sh`
- **Environment Variables**:
  ```bash
  export SPARK_HOME=/home/ubuntu/Jasmine/spark
  export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin
  export SPARK_DIST_CLASSPATH=$(hadoop classpath)
  ```

## Kafka (3.6.1)
- **Installation Directory**: `/home/ubuntu/Jasmine/kafka`
- **Configuration Files**:
  - `kafka/config/server.properties`
  - `kafka/config/zookeeper.properties`
- **Data Directories**:
  - Zookeeper: `/home/ubuntu/Jasmine/kafka/data/zookeeper`
  - Kafka: `/home/ubuntu/Jasmine/kafka/data/kafka`
- **Environment Variables**:
  ```bash
  export KAFKA_HOME=/home/ubuntu/Jasmine/kafka
  export PATH=$PATH:$KAFKA_HOME/bin
  ```

## Flink (1.18.1)
- **Installation Directory**: `/home/ubuntu/Jasmine/flink`
- **Environment Variables**:
  ```bash
  export FLINK_HOME=/home/ubuntu/Jasmine/flink
  export PATH=$PATH:$FLINK_HOME/bin
  ```

## JasmineGraph
- **Source Directory**: `/home/ubuntu/Jasmine/jasminegraph`
- **Build Configuration**: CMake with simplified dependencies
- **Dependencies**:
  - libflatbuffers-dev
  - libyaml-cpp-dev

## Common Environment
- **Java**: OpenJDK 11 (`/usr/lib/jvm/java-11-openjdk-amd64`)
- **System**: Ubuntu Linux
