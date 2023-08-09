# Smart-Irrigation-System
This project stimulates a smart and labour-free method to water plants, and fill water in wells from reservoirs using sensors, actuators and Arduino software. It makes use of 4 sensors: A soil Moisture sensor, a DHT(Humidity and Temperature) sensor, a Raindrop sensor and a Water Level sensor. Each of these is connected to an Arduino UNO board, along with the appropriate actuators(relays, buzzers, water pumps). The following codes are run using Arduino Software. Components used: Soil Moisture sensor, DHT(Humidity and Temperature) sensor, Raindrop sensor, Water Level sensor, Arduino UNO Board, jumper wires, water pumps, relays for water pumps, buzzers to act as actuators for temperature(DHT) and Raindrop sensor. Input-Output Sequence: 1). Soil Moisture Sensor- Input received from soil; in case of low soil moisture, the water pump would begin pumping water into the farm. 2). DHT Sensor: Input received from the air; buzzer would ring at a certain frequency and count if the temperature crossed 25 degrees Celsius. 3). Raindrop Sensor: Input received from drops of water on the sensor(rain), and output is observed as a buzzer(distinct from the previous one) would buzz at a certain frequency(distinct from the previous one) in case of rainfall. 4). Water Level Sensor: Input received via water level in the well; if the water level was observed to be low, the connected water pump would automatically pump water into the well.
