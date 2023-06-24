# LWhero Using NodeRed
LWhero: Laundry warning hero 

## 1. Problem Statement
Housewives often have  to dry clothes outside after the laundry. This can be difficult when the weather is unpredictable or when they don't have a reliable way to check the current conditions. 

To address this problem, we want to build an IoT system that can measure the humidity levels in the air and predict when it is likely to rain, so that housewives can plan their laundry schedules accordingly.

The system should be easy to use, reliable, and accessible from anywhere, and it should provide real-time updates and alerts when rain is predicted. Additionally, the system should be cost-effective and environmentally friendly, using minimal resources and energy to operate.

## 2. System Architecture, sensor & cloud platform
   ![image](https://github.com/faisalhazry/LWhero/assets/128565118/f5893157-85f5-4ffb-a9bb-f9e071cb00a1)

## 3. Mosquitto MQTT Protocol
   The MQTT (Message Queuing Telemetry Transport) protocol works on a publish-subscribe messaging pattern, where publishers send messages to a broker, and subscribers receive messages from the broker. The following steps illustrate how MQTT works:

Establish a connection: The MQTT client (publisher or subscriber) establishes a connection to the MQTT broker using a TCP/IP connection.

Subscribe to a topic: The MQTT client sends a "subscribe" message to the broker, indicating the topic to which it wants to subscribe.

Publish a message: The publisher sends a "publish" message to the broker, including the message payload and the topic to which the message should be sent.

Message routing: The broker receives the "publish" message from the publisher and forwards it to all subscribed clients that have subscribed to the topic.

Unsubscribe: When a subscriber is no longer interested in receiving messages for a particular topic, it sends an "unsubscribe" message to the broker.

Disconnect: When the client is done using the MQTT broker, it sends a "disconnect" message to the broker to close the connection.

## 4. Node-Red
Node-RED is an open-source programming tool designed for visual programming and automation of IoT (Internet of Things) systems. It provides a web-based flow editor that allows users to drag and drop nodes onto a canvas and create a flow that represents a series of events and actions. Each node represents a specific function or service, and the flows connect these nodes to create an automation logic.

## 5. Dashboard Proposal
![image](https://github.com/faisalhazry/LWhero/assets/128565118/c07e385d-1230-4c2f-bb98-65e6e9b967d5)

## 6. Project Budget
![image](https://github.com/faisalhazry/LWhero/assets/128565118/e1488e9b-4e1d-45ae-8dca-b7e9bb460f43)

## 7. Video Stage 2:Cloud Platform Demo

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/A67i4PCis3I/0.jpg)](https://www.youtube.com/watch?v=A67i4PCis3I)


