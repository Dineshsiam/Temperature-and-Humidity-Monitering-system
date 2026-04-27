#  ESP32 Temperature & Humidity Monitor

A simple IoT project using **ESP32** and **DHT11 sensor** to read temperature and humidity data and send it to a server using HTTP requests.


##  Features

*  WiFi connectivity
*  Reads temperature and humidity from DHT11
*  Sends data to a backend server
*  Continuous data transmission
*  Basic error handling for sensor failures


##  Technologies Used

* ESP32
* DHT11 Sensor
* Arduino (C++)
* WiFi & HTTPClient libraries
* ArduinoJson


##  Project Structure

```
 ESP32-DHT11-Monitor
│── main.ino        # Main code
```


##  How It Works

* ESP32 connects to WiFi
* Reads temperature and humidity from DHT11
* Sends data to the server using HTTP request
* Repeats every 5 seconds


##  How to Run

1. Add your WiFi credentials and server URL in the code
2. Upload the code to ESP32
3. Open Serial Monitor to view output

