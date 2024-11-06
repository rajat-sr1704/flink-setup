FROM flink:1.15.0

# Copy the Kafka and MySQL connectors into Flink's lib directory
COPY ./connectors/flink-connector-kafka-1.15.0.jar /opt/flink/lib/
COPY ./connectors/flink-connector-jdbc-1.15.0.jar /opt/flink/lib/
COPY ./connectors/mysql-connector-j-9.1.0.jar /opt/flink/lib/
COPY ./connectors/flink-sql-connector-kafka-1.15.0.jar /opt/flink/lib 