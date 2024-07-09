# Nineti_Assignment
Nineti IoT Internship Assignment - Low Energy Bluetooth Service Broadcasting using ESP32

How to transfer Temperature and Humidity values of a DHT11 Sensor through Bluetooth Low Energy (BLE) using an ESP32 Dev Board, to be viewed on a smartphone. Additionally, connecting to WiFi Hotspot using credentials sent over Bluetooth from smartphone.



Note: Install the necessary libraries (BLE, WiFi, DHT sensor library by Adafruit, BLE2902). Run the codes in the following order to get familiar with the entire process

1) DHT11_Test


2) Bluetooth_DHT11_Broadcasting


3) BLE_DHT11_Text


4) ESP32_DHT11_BLE_WiFi



# Requirements
1) ESP32 Dev Board (or any other Dev board with BLE capabilities)


2) Arduino IDE (or any other board specific IDEs)


3) DHT11 Temperature and Humidity Sensor (or any other sensor with similar capabilities)


4) Jumper wires (optional)


5) Breadboard (optional)


6) 10k ohm pull-up resistor


8) nRF Connect App


9) WiFi availability




# ESP32
![image](https://github.com/KarthikT23/ESP32-Temperature-Humidity-monitoring-system/assets/119528503/c026872d-9985-4b06-a982-0cc67a0ab8a0)

# ESP32 Pinout
![image](https://github.com/KarthikT23/ESP32-Temperature-Humidity-monitoring-system/assets/119528503/2f566421-0116-48fc-9296-51627fb8fd5c)


# Arduino IDE
![image](https://github.com/KarthikT23/ESP32-Temperature-Humidity-monitoring-system/assets/119528503/7cd214b5-981c-48a2-9679-e3f96e476a5e)

# DHT11
![image](https://github.com/KarthikT23/ESP32-Temperature-Humidity-monitoring-system/assets/119528503/dc05c7d4-d01f-4eef-bdd8-ad792a0b4e0c)



# Circuit Diagram
![circuit](https://github.com/KarthikT23/Nineti_Assignment/assets/119528503/fc9e0f46-34ee-4bb5-990b-839eaf408a8e)



Use any GPIO Pin, but mention it correctly in the code!
Connect the Vcc pin of the DHT11 to 3.3V pin of ESP32. Connect the GND pin of DHT11 to GND of ESP32. Connect the Data Pin to GPIO 26, but you can connect it to any other digital pin. Also connect a pull-up resistor of 4.7K ohm to the Data Pin.









# References
1. https://randomnerdtutorials.com/esp32-ble-server-environmental-sensing-service/


2. https://randomnerdtutorials.com/esp32-ble-server-client/


3. https://www.bluetooth.com/specifications/gss/


4. https://randomnerdtutorials.com/esp32-wi-fi-provisioning-ble-arduino/


5. https://forum.arduino.cc/t/questions-about-wifi-and-ble-on-esp32/873395


6. https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-sensor-arduino-ide/


7. https://electronics.stackexchange.com/questions/523376/esp32-receive-ble-data-and-send-via-wifi-possible


8. https://electropeak.com/learn/esp32-setup-wifi-connection-using-bluetooth/
