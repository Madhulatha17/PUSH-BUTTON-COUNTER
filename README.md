# PUSH-BUTTON-COUNTER

## Project Overview

This project demonstrates temperature monitoring using an LM35 temperature sensor and Arduino Uno. The sensor reads ambient temperature and displays the measured value on the Serial Monitor.

## Components Required

* Arduino Uno
* LM35 Temperature Sensor
* Jumper Wires
* USB Cable

## Circuit Connections

* LM35 VCC → Arduino 5V
* LM35 GND → Arduino GND
* LM35 OUT → Arduino A0

## Working Principle

The LM35 sensor generates an analog voltage proportional to temperature. Arduino reads this voltage through the analog input pin and converts it into temperature values displayed on the Serial Monitor.

## Arduino Code

The Arduino program continuously reads sensor data, calculates temperature in Celsius, and prints the result every second.

## Expected Output

Temperature values are displayed on the Serial Monitor in Celsius.

Example:

Temperature: 27.45 °C

Temperature: 27.62 °C

Temperature: 27.55 °C

## Applications

* Weather Monitoring
* Industrial Temperature Measurement
* Home Automation Systems
* Environmental Monitoring

## Outcome

Successfully implemented a temperature monitoring system using Arduino and LM35 sensor with real-time temperature display.
