cax
===

BEMS

Collects temperature data over local MQTT from Sonoff SNZB-02 and SNZB-02D sensors via the Zigbee2MQTT hub.
Collects sensor data and register data from the CIAT ASHP via modbus. 
Subcribes to local MQTT posts and re-publishes to cloud-based HiveMQ.  
Saves all sensor and ASHP downsampled data (i.e. low pass filtered) to influx 
which can be viewed by Grafana. 
Allows ASHP time and temperature settings to be changed over HiveMQ.
