# RPi3*, Home Assistant, MariaDB, Zigbee2MQTT, Mosquitto, Zigbee2MqttAssistant, Node-RED

Change .env variables.

sudo chmod +x configure

sudo ./configure

./restart

...

IP:8123 - Home Assistant
IP:8124 - Zigbee2MqttAssistant
IP:8125 - Node-RED

...

Node-RED >> Manage palette >> node-red-contrib-home-assistant-websocket

* Change Home Assistant Docker image if necessary (docker-compose.yml)
