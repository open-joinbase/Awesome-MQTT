# Awesome MQTT

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of MQTT related stuff.

MQTT is a lightweight client-server publish/subscribe messaging protocol, optimized for high-latency or unreliable networks. This protocol is a good choice for Internet of Things applications, Telemetry, Sensor Networks, Smart Metering, Home Automation, Messaging and Notification Services.

Contents
---

- [Community Resources](#community-resources)
     - [Blogs](#blogs)
     - [Talks](#talks)
- [Broker](#broker)
- [Cloud](#cloud)
- [Platforms](#platforms)
- [Tools](#tools)
- [Clients](#clients)
- [Scripting](#scripting)

## Community Resources

* [mqtt.org](https://mqtt.org/).
* [MQTT community wiki](https://github.com/mqtt/mqtt.org/wiki).
* [Google Groups: MQTT](https://groups.google.com/forum/#!forum/mqtt).
* [IRC channel #mqtt on the freenode network](irc://irc.freenode.net/mqtt).
* [A list of public brokers](http://moxd.io/2015/10/17/public-mqtt-brokers/).

## Blogs

* [Ben Hardill](https://www.hardill.me.uk/wordpress/tag/mqtt/)
* [Dominik Obermaier](http://forkbomb-blog.de/category/mqtt)
* [Jan-Piet Mens](https://jpmens.net/)
* [Nick O'Leary](https://knolleary.net/)

## Talks

* [An Introduction to MQTT: Why HTTP isn't the King of the Internet of Things](https://www.youtube.com/watch?v=LKz1jYngpcU) - Shinji Kim, Robert Bird - Akamai, Samsung Developer Conference 2017.
* [Einführung in MQTT](https://www.youtube.com/watch?v=INYG4-xsa9c) - Dominik Obermaier & Jens Deters, [Building IoT](https://www.buildingiot.de/index.php) conference 2016 (German).

## Broker


|Name|Status|Introduction|
|------|------|------|
|[Ably](https://www.ably.io/documentation/mqtt)|active|MQTT broker service and protocol adapter|
|[ActiveMQ](http://activemq.apache.org/)|active|A fast Java multiprotocol messaging and Integration Patterns server.|
|[Aedes](https://github.com/moscajs/aedes)|active|Barebone MQTT broker that can run on any stream server, the node way.|
|[Emitter](https://github.com/emitter-io/emitter)|inactive|A distributed, scalable and fault-tolerant publish-subscribe messaging platform based on MQTT protocol and featuring message storage.|
|[EMQ X](https://github.com/emqx/emqx)|active|Scalable and Reliable Real-time MQTT Messaging Engine for IoT in 5G Era.|
|[hbmqtt](https://github.com/beerfactory/hbmqtt)|active|Python MQTT broker using asyncio.|
|[HiveMQ](https://www.hivemq.com/)|active|Java MQTT Broker that supports MQTT 3.1, 3.1.1 and 5.0. Commercial and open source editions available.|
|[KMQTT](https://github.com/davidepianca98/KMQTT)|active|Kotlin Multiplatform MQTT broker, both embeddable and standalone.|
|[Moquette](https://github.com/moquette-io/moquette)|active|Java MQTT lightweight broker.|
|[Mosca](http://www.mosca.io/)|active|Mosca is a node.js MQTT broker, which can be used Standalone or Embedded in another Node.js application.|
|[Mosquitto](http://mosquitto.org/)|active|"The"Open Source MQTT Broker. [Free test server](https://mqtt.eclipseprojects.io) hosted by the Eclipse Foundation.[Authorization Plugin in Go](https://github.com/iegomez/mosquitto-go-auth) supports many types of logins.[Let's Encrypt Mosquitto Docker Container](https://hub.docker.com/r/pythonlinks/letsencrypt-mosquitto) makes it easy to encrypt. |
|[MyQttHub](https://myqtthub.com)|active|Cloud MQTT broker.|
|[Mystique](https://github.com/TheThingsIndustries/mystique)|active|An extendable MQTT broker written in Go, with HTTP capabilities for observability. Implements MQTT v3.1.1.|
|[RabbitMQ](https://www.rabbitmq.com/mqtt.html)|active|RabbitMQ offers a MQTT Adapter.|
|[SurgeMQ](https://zhen.org/categories/surgemq/)|active|High Performance MQTT Server and Client Libraries in Go.|
|[VerneMQ](https://vernemq.com/)|active|an Apache2 licensed distributed MQTT broker, developed in Erlang.|
|[Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt)|active|Vert.x component to handle connections, communication and messages exchange with remote MQTT clients.|
|[Waterstream](https://waterstream.io/)|active|MQTT broker leveraging Apache Kafka as its own storage and distribution engine.|
|[NanoMQ](https://github.com/nanomq/nanomq)|active|A light-weight and Blazing-fast MQTT Broker for IoT Edge platform.|

## Cloud

|Name|Status|Introduction|
|------|------|------|
|[Adafruit IO](https://io.adafruit.com)|active|Adafruit IO is the easiest way to connect your project to the internet. You can easily connect your project to Adafruit IO with your device-of-choice by using your programming language of choice (we have lots of libraries) and control or monitor over the internet. Data stored with Adafruit IO is yours to manage and control.|
|[Alibaba Cloud IoT Platform](https://www.alibabacloud.com/product/iot)|active|Provides secure and reliable communication between devices and the IoT Platform which allows you to manage a large number of devices on a single IoT Platform.|
|[AWS IoT Core](https://aws.amazon.com/iot-core/?nc1=h_ls)|active|AWS IoT Core is a managed cloud service that lets connected devices easily and securely interact with cloud applications and other devices. AWS IoT Core can support billions of devices and trillions of messages, and can process and route those messages to AWS endpoints and to other devices reliably and securely. With AWS IoT Core, your applications can keep track of and communicate with all your devices, all the time, even when they aren’t connected.|
|[Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/)|active|Enable highly secure and reliable communication between your IoT application and the devices it manages. Azure IoT Hub provides a cloud-hosted solution backend to connect virtually any device. Extend your solution from the cloud to the edge with per-device authentication, built-in device management, and scaled provisioning.|
|[CloudMQTT](https://www.cloudmqtt.com/)|active|Hosted message broker for the Internet of Things. Perfectly configured and optimized message queues for IoT, ready in seconds.|
|[EMQ X MQTT Cloud](https://cloud.emqx.io/)|active|A secure, reliable MQTT cloud service with best pratices from EMQ team.|
|[flespi](https://flespi.com/mqtt-broker)|active|Free and secure cloud MQTT broker with private namespaces, MQTT 3.1.1 and MQTT 5.0 support and gorgeous limits.|
|[Google Cloud IoT](https://cloud.google.com/solutions/iot/)|active|Google Cloud IoT is a complete set of tools to connect, process, store, and analyze data both at the edge and in the cloud. The platform consists of scalable, fully-managed cloud services; an integrated software stack for edge/on-premises computing with machine learning capabilities for all your IoT needs.|
|[HiveMQ Cloud](https://www.hivemq.com/cloud/)|active|HiveMQ Cloud is a fully managed MQTT platform that connects IoT devices to any IoT cloud platform. A cloud native IoT messaging platform that simplifies reliable and scalable IoT device connectivity.|
|[IBM WATSON](https://www.ibm.com/watson)|active|With Watson, you can bring AI tools and apps to your data wherever it resides – whether it's on IBM Cloud, AWS, Azure, Google, or your own private cloud platform.|

## Platforms

|Name|Status|Introduction|
|------|------|------|
|[JoinBase](https://github.com/open-joinbase)|active|JoinBase is the single binary AIoT-first data-service platform. For Free. 25 million sustained 40B messages per second. Crafted engine is pushing the power of modern hardware to the limit. Interfaces with HTTP, WebSocket, MQTT, PostgreSQL and their TLS variants are available in the highest performance forms.|
|[mainflux](https://www.mainflux.com/)|active|device management, data aggregation, data management, data analytics,connectivity and message routing and event management. Supported by Linux Software Foundation.Core analytics|
|[thingsboard](https://thingsboard.io/)|active|Device management, data collection, processing, event management, and visualization for your IoT projects.|


## Tools

|Name|Status|Introduction|
|------|------|------|
|[hivemq-mqtt-web-client](https://github.com/hivemq/hivemq-mqtt-web-client)|inactive|Browser-based MQTT client that utilizes MQTT over websockets. [Direct Link](http://www.hivemq.com/demos/websocket-client/)|
|[MQTT Board](https://github.com/flespi-software/MQTT-Board)|active|Open-source diagnostic-oriented MQTT client tool.|
|[MQTT CLI](https://github.com/hivemq/mqtt-cli)|active|A command line interface for connecting various MQTT clients supporting MQTT 5.0 and 3.1.1.|
|[mqtt-client](https://github.com/sdeancos/mqtt-client)|active|A Simple MQTT Client command line (Python) (use paho lib)|
|[mqtt-fuzz](https://github.com/F-Secure/mqtt_fuzz)|active|A simple fuzzer for the MQTT protocol.|
|[mqtt-malaria](https://github.com/etactica/mqtt-malaria)|inactive|scalability and load testing utilities for MQTT environments.|
|[mqtt-mirror](https://github.com/4nte/mqtt-mirror)|inactive|Mirror MQTT traffic from one broker to another. Available as a CLI tool, helm chart or docker image.|
|[MQTT-PWN](https://github.com/akamai-threat-research/mqtt-pwn)|inactive|MQTT-PWN intends to be a one-stop-shop for IoT Broker penetration-testing and security assessment operations.|
|[mqtt_recorder](https://github.com/rpdswtk/mqtt_recorder)|inactive|Simple cli tool for recording and replaying MQTT messages.|
|[mqtt_tree](https://github.com/poggenpower/mqtt_tree)|active|Displays all Topics in an expandable tree, helps to get an overview if you have a lot of clients publishing. (python, tkinter)|
|[MQTT.fx](https://mqttfx.jensd.de/)|active|MQTT.fx is a MQTT Client written in Java based on Eclipse Paho. Supports scripting.|
|[mqttcli](https://github.com/shirou/mqttcli)|active|MQTT Client for shell scripting.|
|[MQTTInspector](https://github.com/ckrey/MQTTInspector)|inactive|A general MQTT testing app for iOS (iPhone and iPad).|
|[MQTTLens](https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm)|active|A Google Chrome application, which connects to a MQTT broker and is able to subscribe and publish to MQTT topics.|
|[MQTT Explorer](https://mqtt-explorer.com/)|active|Tool to visualize your MQTT topics in a topic hierarchy, a MQTT swiss-army knife.|
|[MQTT TUI](https://github.com/EdJoPaTo/mqttui)|active|Simple lightweight terminal based MQTT monitor and publisher.|
|[SimpleMQTT](https://simplemqtt.theoi.de/)|active|A Slack app to send messages from Slack to MQTT brokers with slash commands.|
|[MQTTX](https://github.com/emqx/MQTTX)|active|MQTTX is a cross-platform MQTT desktop client open sourced by EMQ, which supports macOS, Linux, and Windows.|
|[MQTT-Tiles](https://github.com/flespi-software/MQTT-Tiles)|active|MQTT-based IoT dashboard visualization tool. Allows easy dashboards sharing. Works with any MQTT broker supporting the WSS protocol.|

### Clients

|Name|Status|Introduction|
|------|------|------|
|[aiomqtt](https://github.com/mossblaser/aiomqtt)|active|Async Python MQTT client based on paho-mqtt.|
|[CocoaMQTT](https://github.com/emqx/CocoaMQTT)|active|MQTT for iOS and OS X written with Swift.|
|[emqttc](https://github.com/emqx/emqtt)|active|Asynchronous Erlang MQTT Client.|
|[gmqtt](https://github.com/wialon/gmqtt)|active|Python MQTT v5.0 client (asyncio-based).|
|[hbmqtt](https://github.com/beerfactory/hbmqtt)|active|Python MQTT client using asyncio.|
|[hivemq-mqtt-client](https://github.com/hivemq/hivemq-mqtt-client)|active|High-performance Java MQTT client library with different API flavours for MQTT 5.0 and 3.1.1.|
|[Hulaaki](https://github.com/suvash/hulaaki)|inactive|An Elixir library for clients communicating with MQTT brokers.|
|[luamqtt](https://github.com/xHasKx/luamqtt/)|active|Pure-lua MQTT v3.1.1 and v5.0 client.|
|[Machine Head](https://github.com/clojurewerkz/machine_head)|active|A Clojure MQTT Client.|
|[MiniMQTT](https://github.com/adafruit/Adafruit_CircuitPython_MiniMQTT)|active|MQTT Client Library for CircuitPython|
|[MIMIC MQTT Simulator](https://www.gambitcomm.com/site/mqttsimulator.php)|active|Simulate up to 100,000 MQTT clients per server for development/testing/deployment of IoT applications.|
|[Moscapsule](https://github.com/flightonary/Moscapsule)|inactive|MQTT Client for iOS written in Swift.|
|[mqtt_cpp](https://github.com/redboltz/mqtt_cpp)|active|MQTT client for C++14 based on Boost.Asio.|
|[mqtt_lua](http://geekscape.github.io/mqtt_lua/)|active|MQTT Client library for the Lua language.|
|[MQTT-C](https://github.com/LiamBindle/MQTT-C)|active|A portable MQTT C client for embedded systems and PCs alike.|
|[mqtt-rs](https://github.com/zonyitoo/mqtt-rs)|active|MQTT protocol library for Rust.|
|[mqtt-stats](https://github.com/gambitcomminc/mqtt-stats)|inactive|Subscriber client to monitor MQTT Topic Statistics|
|[mqtt-wrapper](https://www.webcomponents.org/element/hobbyquaker/mqtt-wrapper/elements/mqtt-wrapper)|active|Polymer Element that wraps other Elements and links them to MQTT topics.|
|[MQTT.js](https://github.com/mqttjs)|active|MQTT client for Node.js.|
|[mqtt_monitor](https://github.com/filipsPL/mqtt-monitor)|active|simple and lightweight console moniotor for mqtt topics, with eye-candies, in python 3.|
|[Paho](http://www.eclipse.org/paho/)|active|Open source client implementations (C/C++, Java, Python, Javascript, Go, C#).|
|[pubsubclient](https://github.com/knolleary/pubsubclient)|inactive|A client library for the Arduino Ethernet Shield that provides support for MQTT.|
|[ruby-mqtt](https://github.com/njh/ruby-mqtt)|active|Pure Ruby gem that implements the MQTT protocol.|
|[Vert.x MQTT](https://github.com/vert-x3/vertx-mqtt)|active|Vert.x component that provides methods for connecting/disconnecting to a broker, publishing messages and subscribing to topics.|
|[wolfMQTT](https://www.wolfssl.com/products/wolfmqtt/)|active|A client implementation of the MQTT written in C for embedded use. It supports SSL/TLS via the wolfSSL library.|
|[MQTTnet](https://github.com/chkr1011/MQTTnet)|active|MQTT client and broker implementations in .NET.|

### Scripting

|Name|Status|Introduction|
|------|------|------|
|[logic4mqtt](https://github.com/owagner/logic4mqtt)|inactive|Node.js based script runner.|
|[Node-RED](https://nodered.org/)|active|A visual tool for wiring the Internet of Things.|
