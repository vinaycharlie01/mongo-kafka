docker exec -it ksql-cli ksql http://0.0.0.0:8088
docker exec -it kafka kafka-topics --list --bootstrap-server localhost:9092
docker exec -it broker kafka-topics --list --bootstrap-server localhost:9092

docker exec -it kafka kafka-topics --list --bootstrap-server localhost:9092

docker exec -it broker kafka-console-consumer --bootstrap-server localhost:9092 --topic topicname --from-beginning