# Socialhardware

###Features 
- [Pairs with MQTT broker] (https://github.com/nullboundary/pesand)
- Restful API
- Websocket realtime browser updates
- Conditional triggers
- [Esp8266 hardware sensor example] (https://github.com/nullboundary/SensorApi-esp8266)

###Status
- Beta

###TODO
- Add option to use boltdb for easier install
- Make MQTT broker optional
- Release crossplatform binaries

--

### Default Stream view
- The browser client uses websockets to stream realtime incoming data to the zoomable d3.js graph and data log. 

![Image](docs/images/socialhw1.png?raw=true)

--
### Add stream trigger
- A user can configure triggers for each stream, to execute an api request if a condition has been met with the streaming data. 

![Image](docs/images/socialhw3.png?raw=true)

--
### Add new stream
![Image](docs/images/socialhw2.png?raw=true)
