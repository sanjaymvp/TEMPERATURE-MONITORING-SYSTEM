# TEMPERATURE-MONITORING-SYSTEM

COMPANY:CODTECH IT SOLUTIONS

INTERN ID : CT04DH8046

DOMAIN : EMBEDDED SYSTEMS

DURATION : 4 WEEKS

MENTOR:NEELA SANTHOSH

TASK DESCRIPTION:The main task of this project is to measure and display ambient temperature in real-time. The LM35 sensor senses the temperature and outputs a corresponding analog voltage. The Arduino reads this voltage, processes it to calculate the temperature in Celsius, and then displays it on an I2C LCD screen. The LCD shows the temperature value clearly, refreshing every two seconds to provide up-to-date readings. This setup can be used for monitoring room temperature or other temperature-sensitive environments. The use of I2C communication with the LCD also makes the project efficient in terms of wiring and pin usage, making it ideal for compact and educational temperature sensing applications.

WORKING PRINCIPLE:This temperature monitoring system operates using an LM35 temperature sensor, which generates an analog voltage output proportional to the surrounding temperature at a rate of 10mV per °C. The Arduino Uno reads this analog voltage through pin A0 and converts it into a digital value using its internal ADC (Analog-to-Digital Converter). The digital value is then converted into voltage and further into temperature in Celsius using the formula: temperature (°C) = voltage × 100. This processed temperature value is then sent to a 16x2 LCD screen for display. The LCD uses I2C communication, allowing it to interface with the Arduino using only two pins (SDA and SCL), simplifying the wiring. The system continuously monitors the temperature and updates the display every two seconds, providing real-time temperature data.
