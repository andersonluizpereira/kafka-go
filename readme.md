#Create topic
kafka-topics --create --bootstrap-server=localhost:9092 --topic=teste --partitions=3

#View messages topic with consumer
kafka-console-consumer --bootstrap-server=localhost:9092 --topic=teste
# kafka-go

#test consumer
open 3 layer`s, modify goapp-consumer and 1,2,3

Kill consumer default goapp-consumer, wait r Consumer group 'goapp-group' is rebalancing.e

"client.id":"goapp-consumer",