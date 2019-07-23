# NodeMCU-AlexaDevice
Use a NodeMCU (ESP-12E) to control literally Anything in your house by turning into a Smart Switch.
View my video tutorial on YouTube for more information: https://youtu.be/0Z1pR3cehHQ

### What you will Need:
 1. NodeMCU - http://a.co/d/eVLpLl1
 2. Mini USB Cables - http://a.co/d/7UUkQWU
 3. Arduino IDE - https://www.arduino.cc/en/Main/Software
 
### STEP 1: Connecting NodeMCU to Arduino IDE

1. Download or Clone Repository
2. Download and Include the following Libraries:
 - #include <WebSocketsClient.h> //  https://github.com/kakopappa/sinric/wiki/How-to-add-dependency-libraries
 - #include <ArduinoJson.h> // https://github.com/kakopappa/sinric/wiki/How-to-add-dependency-libraries
3. Open Arduino.IDE and go to Board Manager > ESP8266 and get boards
4. Open the sketch needed (NodeMCU-Alexa.ino)
4. Upload to NodeMCU chip

### STEP 2: Controlling NodeMCU with Alexa

1. Register for an account (https://sinric.com) if you do not have one (Use Chrome, FireFox)

2. Login and create a smart home device (Dashboard -> Add smart home device)

3. Copy your API Key from dashboard

4. Connect to Sinric IOT server - Use NodeMCU-Alexa.ino sketch. For other examples:  https://github.com/kakopappa/sinric/blob/master/arduino_examples

5. Change the Arduino Sketch. Replace the API Key, Wifi SSID and Password

6. Change the Device ID in Arduino Code to that supplied on Sinric website

7. Install Amazon Alexa Smart Home Skill (Available in US, German, India, UK, Canada, Australia, New Zealand, Italy) here and Link to your Sinric account. https://www.amazon.com/dp/B078RGYWQQ

8. Discover for new devices.
