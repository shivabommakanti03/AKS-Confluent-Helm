## Installing Confluent Kafka with Monitoring

```
# Default settings
helm upgrade --install <release_name> . --namespace <your_namespace>
```

```
# Set number of broker and/or zookeeper instances
helm upgrade --install <release_name> . --namespace <your_namespace> --set cp-kafka.brokers=3,cp-zookeeper.servers=3
```
