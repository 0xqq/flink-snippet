# kafka

## How to use
for instance:
```shell
> java -cp flink-snippet-kafka_0.0.1.jar gx.kafka.producer.SimpleCsvProducer --records 10000 --topic gxtest --bootstrap.servers zdh16en:9092
```

monitor a kafka topic:
```shell
> kafka-console-consumer --bootstrap-server zdh16en:9092 --topic gxtestout  --zookeeper zdh16en:2181/kafka
```


## Producer List

| main class                             | description                                             |
|----------------------------------------|---------------------------------------------------------|
| gx.kafka.producer.SimpleCsvProducer    | Produce csv fromat (comma-split) records.               |
| gx.kafka.producer.SimpleJsonProducer   | Produce json format records.                            |
| gx.kafka.producer.SimpleWordProducer   | Produce simple string records.                          |


