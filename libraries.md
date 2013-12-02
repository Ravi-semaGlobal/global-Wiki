##  Libraries 

`<note>`Note: although there are a range of options available for developers interested in MQTT, not all of the client APIs listed below are current. Some are at an early or experimental stage of development, whilst others are stable and mature. Additionally, some may not provide full support for all of the features of the latest MQTT specification – for example, some may only support QoS 0, not include authentication, etc.`</note>`

Check with the provider for the current status of your preferred language implementation; and remember to respect the licenses that different implementations are published under.

** Device-Specific **

*  [Arduino](https///github.com/knolleary/pubsubclient) ([more information](http://knolleary.net/arduino-client-for-mqtt/))

*  [mbed](https///github.com/yilun/MQTT-client-on-mbed) ([more information](http://ceit.uq.edu.au/content/mqttclient-mbed-version-20))

*  [mbed (simple port of the Arduino pubsubclient)](http://mbed.org/users/jwende/code/MQTT/)

*  [Nanode](http://github.com/njh/NanodeMQTT/)

*  [Netduino](https///github.com/danielan/NetduinoMQTT)

*  [M2MQTT (works with .Net Micro Framework)](https///m2mqtt.codeplex.com/)

(see also [devices](things) page for more on hardware with built-in support)

** Actionscript **

*  [as3MQTT](https///github.com/yangboz/as3MQTT)

** C **

*  [Eclipse Paho](http://git.eclipse.org/c/paho/org.eclipse.paho.mqtt.c.git/)

*  [libmosquitto](http://mosquitto.org)

*  [libemqtt](https///github.com/menudoproblema/libemqtt) - an embedded C client

** C++ **

*  [libmosquittopp](http://mosquitto.org)

** Clojure **

*  [Machine Head](http://clojuremqtt.info)

** Dart **

*  [mqtt.dart](http://pub.dartlang.org/packages/mqtt)

** Delphi **

*  [TMQTTClient](http://jamiei.com/code/TMQTTClient.zip) ([more information](http://jamiei.com/blog/code/mqtt-client-library-for-delphi/))

** Erlang **

*  [erlmqtt](https///github.com/squaremo/erlmqtt)

*  [mqtt4erl](http://code.google.com/p/mqtt4erl/)

*  [my-mqtt4erl](http://code.google.com/p/my-mqtt4erl/) - updated fork of mqtt4erl

** Java **

*  [Eclipse Paho](http://git.eclipse.org/c/paho/org.eclipse.paho.mqtt.c.git/)

*  [Xenqtt](http://xenqtt.sf.net) Includes a client library, mock broker for unit/integration testing, and applications to support enterprise needs like using a cluster of servers as a single client, an HTTP gateway, etc.

*  [MeQanTT](https///github.com/AlbinTheander/MeQanTT)

*  [Fusesource mqtt-client](https///github.com/fusesource/mqtt-client)

*  [moquette](http://code.google.com/p/moquette-mqtt/)

*  [ "MA9B" zip of 1/2 dozen mobile clients source code. Includes Android-optimized Java source that works with Android notifications, based on Paho](http://www-933.ibm.com/support/fixcentral/swg/selectFix?product=ibm%2FWebSphere%2FWebSphere+MQ&fixids=1.0.0.1-WS-MQCP-MA9B&source=dbluesearch&function=fixId&parent=ibm/WebSphere )

*  [IA92](http://www-01.ibm.com/support/docview.wss?rs=171&uid=swg24006006&loc=en_US&cs=utf-8&lang=en) - *deprecated* IBM IA92 support pack, use Eclipse Paho GUI client instead. A useful MQTT Java swing GUI for publishing & subscribing. The Eclipse Paho GUI is identical but uses newer client code

** Javscript / Node.js **

*  [Eclipse Paho HTML5 JavaScript for MQTT over WebSocket.](http://eclipse.org/paho/)

*  [mqtt.js](https///github.com/adamvr/MQTT.js)

*  [node_mqtt_client](https///github.com/yilun/node_mqtt_client) ([more information](http://ceit.uq.edu.au/content/simple-mqtt-cient-nodejs))

*  [IBM-provided PhoneGap / Apache Cordova MQTT plug-in for Android](http://www-01.ibm.com/support/docview.wss?rs=171&uid=swg24033580&loc=en_US&cs=utf-8&lang=en) - JavaScript API is identical to Eclipse Paho HTML5 JavaScript

*  [mosquitto websocket client](http://mosquitto.org/js/mosquitto-1.0.js) (//deprecated//, use Eclipse Paho)

*  [Ascoltatori](https///github.com/mcollina/ascoltatori) - a node.js pub/sub library that allows access to Redis, AMQP, MQTT and ZeroMQ with the same API.

** LotusScript **

*  [MQTT From LotusScript](https///tingenek.wordpress.com/2011/11/30/mqtt-with-lotus-notes/)

** Lua **

*  [Eclipse Paho Lua client](http://eclipse.org/paho/)

*  [mqtt_lua](https///github.com/geekscape/mqtt_lua) (//deprecated// use Paho)

** .NET / dotNET **

*  [MqttDotNet](http://sourceforge.net/projects/mqttdotnet/)

*  [nMQTT](https///github.com/markallanson/nmqtt)

*  [M2MQTT](https///m2mqtt.codeplex.com/)

** Objective-C **

*  [mqttIO-objC](https///github.com/m2mIO/mqttIO-objC)

*  [libmosquitto](https///mosquitto.org) - via wrappers ([example](https///github.com/njh/marquette))

*  [MQTTKit](https///github.com/jmesnil/MQTTKit) ([sample app](https///github.com/jmesnil/MQTTExample))

*  ["MA9B" zip of 1/2 dozen mobile clients source code including Objective-C](http://www-933.ibm.com/support/fixcentral/swg/selectFix?product=ibm%2FWebSphere%2FWebSphere+MQ&fixids=1.0.0.1-WS-MQCP-MA9B&source=dbluesearch&function=fixId&parent=ibm/WebSphere)

** Perl **

*  [net-mqtt-perl](https///github.com/beanz/net-mqtt-perl)

*  [anyevent-mqtt-perl](https///github.com/beanz/anyevent-mqtt-perl)

*  [WebSphere-MQTT-Client](http://search.cpan.org/dist/WebSphere-MQTT-Client/)

** PHP **

*  [phpMQTT](http://github.com/bluerhinos/phpMQTT)

*  [Mosquitto-PHP](https///github.com/mgdm/Mosquitto-PHP)

** Python **

*  [Eclipse Paho Python client](http://eclipse.org/paho/) - originally the mosquitto Python client

*  [python-mosquitto](http://mosquitto.org/documentation/python) (//deprecated// use Paho code)

*  [nyamuk](https///github.com/iwanbk/nyamuk)

*  [MQTT for twisted python](https///github.com/adamvr/MQTT-For-Twisted-Python)

** REXX **

*  [REXX MQTT](https///github.com/DougieLawson/REXX_MQTT)

** Ruby **

*  [ruby-mqtt](https///github.com/njh/ruby-mqtt)

*  [em-mqtt](https///rubygems.org/gems/em-mqtt)

** Tcl **

*  [tcl-mqtt](https///github.com/Tingenek/tcl-mqtt)