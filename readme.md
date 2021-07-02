#Create topic
kafka-topics --create --bootstrap-server=localhost:9092 --topic=teste --partitions=3

#View messages topic with consumer
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=teste
# kafka-go
