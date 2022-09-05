# growatt_mqtt_rs232

Read inverter data with ESP8266 from RS232 port on a S-Series Growatt inverter

# Growatt Solar Inverter parameters from RS232 to MQTT topics

Currently in proto stage on a Growatt 3000-S inverter 

Hardware:
- Wemos D1 mini (ESP-8266EX)
- RS232-TTL Converter
- Some wires and solder
- TX/Rx configuration is 13/12 (can be configured in the SoftwareSerial pin definition (SS_RX and SS_TX))

Code structure based on: https://github.com/jkairys/growatt-esp8266/tree/master/deprecated
