FROM apache/flink:1.12-scala_2.12-java11

RUN apt-get update -y && apt-get install -y wget && rm -rf /var/lib/apt/lists/*
RUN wget https://repository.cloudera.com/artifactory/libs-release-local/org/apache/flink/flink-shaded-hadoop-3-uber/3.1.1.7.1.1.0-565-9.0/flink-shaded-hadoop-3-uber-3.1.1.7.1.1.0-565-9.0.jar -P /opt/flink/lib/