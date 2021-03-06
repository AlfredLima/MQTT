# IOT
Learning about MQTT and NodeMCU.

## MQTT

### Install Mosquitto Broker
- sudo apt install mosquitto
- sudo apt install mosquitto-clients

### Configure Mosquitto
- http://www.steves-internet-guide.com/install-mosquitto-linux/
- https://www.dobitaobyte.com.br/iot-configurando-um-mqtt-broker/
- https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-the-mosquitto-mqtt-messaging-broker-on-ubuntu-16-04

### Enable server
- sudo systemctl enable mosquitto.service

### Query
- systemctl status mosquitto.service

### Publisher
- mosquitto_sub -h IP -t "TOPIC" -m "MESSAGE"

### Subcribe
- mosquitto_sub -h IP -t "TOPIC"

### Install HiveMQ Broker
- https://www.hivemq.com/docs/hivemq/latest/#hivemqdocs_installation_for_specific_operating_systems

### Configure HiveMQ
- https://www.hivemq.com/docs/hivemq/latest/#hivemqdocs_linux_configuration

## Node MCU

### Pins with IDE Arduino
- D0: 16
- D1: 5
- D2: 4
- D3: 0
- D4: 2
- D5: 14
- D6: 12
- D7: 13
- D8: 15
- D9: 3
- D10: 1

### PubSubClient Library
- Publish
- Subcribe