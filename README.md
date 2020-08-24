
# MicroService -EventSourcing Implementation using Node.js,Kafka

  

### Technologies Used

  

- Node.js

- Kafka

- MongoDB

  
  

### Dependencies

  

- [Node.js](https://nodejs.org/en/download/)

- [Kafka](https://kafka.apache.org/downloads)

  
  

### To Run Application

  

#### Kafka

  

```

  

$ bin/zookeeper-server-start.sh config/zookeeper.properties

$ bin/kafka-server-start.sh config/server.properties

  
  

OR

  

$ zkserver

$ .\bin\windows\kafka-server-start.bat .\config\server.properties

  

```

  

#### Producer

```

  

$ cd node-kafka-producer/

$ npm i

$ node server.js

  

```

  

#### Consumer

```

  

$ cd node-kafka-consumer/

$ npm i

$ node server.js

```


[# Setting Up and Running Apache Kafka on Windows OS ](#%20MicroService%20-EventSourcing%20Implementation%20using%20Node.js,Kafka%20%20###%20Technologies%20Used%20%20%20%20%20%20-%20Node.js%20%20%20%20%20-%20Kafka%20%20%20%20%20-%20MongoDB%20%20%20###%20Dependencies%20%20%20%20%20%20-%20%5BNode.js%5D%28https://nodejs.org/en/download/%29%20%20%20%20%20-%20%5BKafka%5D%28https://kafka.apache.org/downloads%29%20%20%20###%20To%20Run%20Application%20%20####%20Kafka%20%20%60%60%60%20%20$%20%20bin/zookeeper-server-start.sh%20config/zookeeper.properties%20$%20%20bin/kafka-server-start.sh%20config/server.properties%20%20%20OR%20%20%20$%20%20zkserver%20$%20.%5Cbin%5Cwindows%5Ckafka-server-start.bat%20.%5Cconfig%5Cserver.properties%20%20%60%60%60%20%20####%20Producer%20%60%60%60%20%20$%20cd%20node-kafka-producer/%20$%20npm%20i%20%20$%20node%20server.js%20%20%60%60%60%20%20####%20Consumer%20%60%60%60%20%20$%20cd%20node-kafka-consumer/%20$%20npm%20i%20$%20node%20server.js%20%20%60%60%60)