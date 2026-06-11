# ESP32 Mini Weather Station

A simple weather station built using ESP32, DHT22 sensor, and OLED display. The project reads temperature and humidity data from the DHT22 sensor and displays it on a 0.96" OLED screen in real time.

## Features

- Real-time temperature monitoring
- Real-time humidity monitoring
- OLED display output
- ESP32-based IoT project
- Beginner-friendly implementation

## Components Used

- ESP32 Development Board
- DHT22 Temperature & Humidity Sensor
- 0.96" OLED Display (I2C)
  


## Circuit Connections

### DHT22 to ESP32

| DHT22 Pin | ESP32 Pin |
|------------|----------|
| VCC        |  3.3V    |
| GND        | GND      |
| DATA       | GPIO 15  |

### OLED to ESP32

| OLED Pin | ESP32 Pin |
|-----------|-----------|
| VCC       | 3.3V      |
| GND       | GND       |
| SDA       | GPIO 21   |
| SCL       |  GPIO 22  |

## Working

1. ESP32 reads temperature and humidity from the DHT22 sensor.
2. Sensor data is processed by the ESP32.
3. The OLED display shows:
   - Temperature (°C)
   - Humidity (%)
4. Data updates continuously in real time.

## Software Used
- ESP32 Board Package
- Wokwi Simulator

## Project Output

The OLED display shows:

Temperature: 28°C
Humidity: 65%

(Values change according to sensor readings.)

## Future Improvements

- Add Wi-Fi support
- Send data to cloud platforms
- Add weather alerts
- Display historical data

## Author

Ramandeep Kaur
