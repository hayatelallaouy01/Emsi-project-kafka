# Emsi kafka spring cloud project
---------------------
## Procedure
+ On the computer where Apache Kafka is installed, log on as the root user.
+ Go to the kafka_ directory.
+ Enter the following command to start the zookeeper process: bin/zookeeper-server-start.sh config/zookeeper.properties
+ Enter the following command to start the Kafka process: bin/kafka-server-start.sh config/server.properties
## Project Dependencies
The project uses the following entities and services:
+ PageEvent class in the entities folder.
+ PageEventService class in the services folder, which includes functions for consuming, supplying, and processing page events.
+ PageEventRestController class in the web folder, responsible for handling REST endpoints.
+ index.html in the resources/static folder, displaying a Smoothie.js graph.
+ Configuration details in application.properties.
### kafka commandes 
-------
```powershell
C:\kafka_2.13-3.6.1>start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R1
C:\kafka_2.13-3.6.1>start bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic R1
C:\kafka_2.13-3.6.1>start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R2
C:\kafka_2.13-3.6.1>start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R3
C:\kafka_2.13-3.6.1>start .\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R4 --property print.key=true --property print.value=true --property key.deserializer=org.apache.kafka.common.serialization.StringDeserializer --property value.deserializer=org.apache.kafka.common.serialization.LongDeserializer
```
![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/c948e070-3d0c-4206-b9d1-67278d038c08)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/f60e8cb2-788a-4a54-a44d-0f761a81be6e)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/34dc43de-da60-40cc-b921-89dd1c90ecab)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/abbb91ba-020c-46ea-b962-3a44aaaf94fd)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/4c715a5b-42e4-4999-bd7f-0b68c5feea75)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/4d832e76-6239-4c8f-b890-86efb4e7fc8b)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/8165baf4-2016-44a8-afa3-512f346b4918)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/a29e85bc-65b2-4fdd-a556-b8cfb4affc0e)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/945ca377-64e1-41be-a208-b6d3ecffe739)

![image](https://github.com/hayatelallaouy01/Emsi-project-kafka/assets/123452386/8b8d7ea9-8272-4483-a6ad-b7d701a38810)











