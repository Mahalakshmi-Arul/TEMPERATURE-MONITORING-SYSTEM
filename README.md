# TEMPERATURE_MONITORING_SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MAHALAKSHMI A

*INTERN ID*: CT04DA198

*DOMAIN*: EMBEDDED SYSTEMS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*: Implemented a simple temperature monitoring system using an Arduino Uno and a TMP36 analog temperature sensor. The sensor is connected to analog pin A0, and its readings are processed to calculate temperature in Celsius. The real-time temperature value is then displayed on a 16x2 I2C LCD screen. The project was developed using basic analog read logic and floating-point computation, with periodic updates on the LCD.

*KEY FEATURES*:
➤ Reads analog voltage from TMP36 sensor (connected to A0)
➤ Converts sensor value to Celsius temperature using linear conversion
➤ Displays updated temperature value every second
➤ Uses I2C protocol to interface 16x2 LCD for simplified wiring
➤ No unit symbol or Fahrenheit conversion included (as per implementation)
➤ Temperature displayed in integer format for clarity
➤ Uses modular lcd.setCursor() and lcd.print() functions to position output

*PERIPHERALS USED*:
• TMP36 Analog Temperature Sensor (connected to A0)
• 16x2 I2C LCD Display (address: 0x20)
• Arduino Uno Board
• I2C Lines: SDA and SCL (A4 and A5 on Arduino Uno)

