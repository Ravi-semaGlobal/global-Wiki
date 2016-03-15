# Servers/Brokers

## IBM Websphere MQ Telemetry

The Telemetry MQTT feature is built-in optionally licensed feature in 
[WebSphere MQ](http://www-01.ibm.com/software/integration/wmqfamily/telemetry/ ) version 7.1 and above. It provides full MQTT v3.1 support, IBM MQ and JMS support. IBM WebSphere MQ Advanced includes the MQTT license at no charge. It ships with reference Java (MIDP and above), C and JavaScript (MQTT over WebSocket) clients.  Eclipse Paho is highly recommended by IBM.

## IBM MessageSight

[ IBM MessageSight](http://www.ibm.com/messagesight ) is a DMZ secure MQTT appliance with hardware messaging acceleration for M2M and mobile applications requiring extreme volume, low latency, FIPS 140-2 and NSA Suite B security. Messaging provider for MQTT, HTML5 WebSockets, JMS. Includes C, Java, JavaScript, Apache Cordova/PhoneGap, ObjectiveC clients. Also connects/bridges IBM MQ, IBM Integration Bus, WebSphere MessageBroker.

## IBM Integration Bus

[ IBM Integration Bus](http://www-03.ibm.com/software/products/us/en/integration-bus/ ) V9 has Telemetry feature built-in as optional licensed feature.  IBM WebSphere MessageBroker V7 & V8 also include it as optionally licensed feature.

[ Really Small Message Broker](http://www.alphaworks.ibm.com/tech/rsmb )\\
75KB MQTT broker runtime free download as binaries from IBM alphaWorks, RSMB is a C implementation of a tiny MQTT server suitable for development, embedded systems, concentrators or small to medium sized deployments. It provides complete MQTT v3.1 support, bridging, and a C client API.

## Mosquitto

[ Mosquitto](http://mosquitto.org ) is an Open Source MQTT server with C, C++, Python.  For JavaScript, Mosquitto recommends the Eclipse Paho Javascript client. A public, hosted test server is also available ([more information](public_brokers))

## Eclipse Paho

The [ Eclipse Paho](http://www.eclipse.org/paho/ ) project hosts an instance of the mosquitto broker as a public test sandbox for the [Machine-to-Machine Industry Working Group](http://m2m.eclipse.org/) ([more information](public_brokers)).

## Eurotech Everywhere Device Cloud

[Eurotech Everywhere Device Cloud](http://www.eurotech.com/en/solutions/device+to+cloud/mqtt+protocol) is a cloud-based service provided by [Eurotech](http://www.eurotech.com).

## emqttd

[emqttd](https://github.com/emqtt/emqttd) is a massively scalable and clusterable MQTT V3.1/V3.1.1 broker written in Erlang/OTP. Latest release(0.17) of emqttd broker is scaling to 1.3 million MQTT connections on a 12 Core, 32G CentOS server.

emqttd is fully open source and licensed under the Apache Version 2.0. emqttd implements both MQTT V3.1 and V3.1.1 protocol specifications, and supports WebSocket, STOMP, SockJS, CoAP and MQTT-SN at the same time.

The emqttd project provides a scalable, distributed, extensible open-source MQTT broker for IoT, M2M and Mobile applications that hope to handle millions of concurrent MQTT clients.

## Xively

The [ Xively](http://xively.com ) service, formerly known as Cosm, formerly known as Pachube, provides a data cloud for the Internet of Things, with MQTT support in beta. This is not a generic MQTT broker implementation; it uses MQTT as a transport for publishing and subscribing to your already existing data feeds ([more information](mqtt_and_pachube)).

## Yunba.io

[ Yunba](http://yunba.io/) is a backend cloud platform that provides real-time message dispatch service to mobile applications and devices and uses MQTT as a transport protocol, The services include bi-directional push for Instant-Messaging; real-time analyzing; real-time online monitoring.

## m2m.io

[ m2m.io](http://m2m.io ) is a cloud messaging service ([more information](public_brokers)).

## webMethods Nirvana Messaging

[ webMethods Nirvana Messaging](http://www.my-channels.com/products/nirvana.html ) provides a messaging engine with support for many different transports. Their MQTT support is described in their [blog](http://blog.my-channels.com/2012/01/27/mqtt-support-in-nirvana-7/).

## RabbitMQ

[ RabbitMQ](http://rabbitmq.com/ ) is an AMQP message broker – with an [MQTT plugin](http://www.rabbitmq.com/blog/2012/09/12/mqtt-adapter/) (bundled in version 3.x onwards). A public test server is also available ([more information](public_brokers)).

## Apache ActiveMQ

Details of “classic” [ ActiveMQ’s](http://activemq.apache.org/index.html ) support for MQTT are available [here](http://activemq.apache.org/mqtt.html).

## Apache Apollo

The “next generation” of ActiveMQ, [ Apache Apollo](http://activemq.apache.org/apollo/ ), supports MQTT via a [plugin](https://github.com/fusesource/fuse-extra/tree/master/fusemq-apollo/fusemq-apollo-mqtt).

## Moquette

[ Moquette](http://code.google.com/p/moquette-mqtt/ ) is a Java MQTT broker based on an eventing model with Apache Mina.

## HiveMQ

[ HiveMQ](http://www.hivemq.com/ ) is a MQTT broker which was built from the ground up with maximum scalability and enterprise-ready security in mind. It comes with native web socket support and an open source plugin SDK to extend its functionality or integrate it with other components. A public test server is also available ([more information](public_brokers)).

## Mosca

As node.js MQTT broker can [ Mosca](https://github.com/mcollina/mosca ) be plugged on top of Redis, AMQP, MQTT, or ZeroMQ.

## Litmus Automation Loop

[ Loop](http://litmusautomation.com ) is a cloud based MQTT broker with scalability, high availability and security at core. Loop provides full MQTT 3.1 support and JMS connectivity. It can handle extremely large numbers of connected clients. On the other side it can be connected to any ERP, CRM and enterprise architecture with ESB or NoSQL databases for blazing fast data storage.

## JoramMQ

[JoramMQ](http://mqtt.jorammq.com) is an offering by ScalAgent providing a message broker that fully supports MQTT 3.1, JMS 2.0, and AMQP 1.0. Interoperability between these standards is ensured by the message broker. MQTT can be used over TCP/IP, TLS (SSL), WebSocket, and secure WebSocket. JoramMQ is particularly appropriate for applications that need to scale with the number of MQTT clients while allowing the publishers to reliably transmit a large volume of messages with a low latency.

## Solace

[Solace Message Routers](http://dev.solacesystems.com/tech/) (available as hardware and software) are message brokers that support MQTT, JMS, and REST among other APIs, protocols and qualities of service for enterprise messaging, data collection and web/mobile streaming. They support very high connection counts and throughput with built-in buffering to handle bursty traffic, and offer enterprise-class monitoring, high availability and security.

## ThingMQ

[ThingMQ](https://thingmq.com) is a carrier-grade MQTT message broker that runs on the cloud. It supports the MQTT 3.1 standard as well as CoAP, REST and WebSockets. Messages published on ThingMQ using MQTT are automatically bridged and can be consumed using CoAP, REST or WebSockets. A shared instance of ThingMQ is offered free of charge.

## VerneMQ

[VerneMQ](http://verne.mq) is an enterprise ready, high-performance, distributed MQTT message broker. It scales horizontally and vertically on commodity hardware to support a high number of concurrent publishers and consumers while maintaining low latency and fault tolerance. VerneMQ is Apache2 licensed.

## HBMQTT

[HBMQTT](https://github.com/beerfactory/hbmqtt) is an open-source implementation of MQTT broker and client. It uses Python 3.4+ asyncio library for providing a mono-threaded, non-blocking implementation of the protocol.

**More information on brokers**


*  [compare the capabilities](server-support) of different brokers

*  see some of the [public brokers](public_brokers) available for testing on the wiki