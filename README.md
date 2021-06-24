# Designing an Accelerometer Patch using ESP32 & MPU6050
 Building MOCAP sensors.
 
 Project built upon by using this link https://RandomNerdTutorials.com/esp32-mpu-6050-web-server/

## Project Overview
- Gyroscope values of the X, Y an Z axis are displayed on the Web Server (Updated every 10ms).
- Accelerometer values (Updated every 200ms).
- Temperature is updated every second.
- We use Server-Sent Events to update all the readings.
- The 3D object is created using a JavaScript library called [three.js](https://threejs.org).

## Update Network Credentials
```
// Replace with your network credentials
const char* ssid = "REPLACE_WITH_YOUR_SSID";
const char* password = "REPLACE_WITH_YOUR_PASSWORD";
```
### Screenshots
<img width="400" alt="1" src="https://user-images.githubusercontent.com/68840837/123207296-cc458800-d4da-11eb-8496-1bcdbb72e0ed.png">
<img width="400" alt="2" src="https://user-images.githubusercontent.com/68840837/123207303-cf407880-d4da-11eb-9d2b-39fdcd3a3cab.png">
