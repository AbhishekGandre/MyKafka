# MyKafka

<h2>Create the Zookeeper</h2> 
<h3>C:\kafka\kafka>bin\windows\zookeeper-server-start.bat config\zookeeper.properties</h3>


<h2>Create the Kafka Server</h2> 
<h3>C:\kafka\kafka>bin\windows\kafka-server-start.bat config\server.properties</h3>

<h2>Create the Topics in kafka</h2> 
<h3>C:\kafka\kafka>bin\windows\kafka-topics.bat --create --topic abhishek-p1 --bootstrap-servver localhost:9092</h3>


<h2>Create the Kafka-Producer</h2> 
<h3>C:\kafka\kafka>bin\windows\kafka-console-producer.bat --topic abhishek-p1 --bootstrap-server localhost:9092</h3>


<h2>Create the Kafka-Consumer</h2> 
<h3>C:\kafka\kafka>bin\windows\kafka-console-consumer.bat --topic abhishek-p1 --from-beginning --bootstrap-server localhost:9092</h3>