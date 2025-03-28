# 1132CFiot
This class has two hands-on exercises: **1. Connect IoT to AWS Cloud**. **2. Facial recognition**. The first exercise familiarizes students with IoT and AWS IoT platforms; the second experiences artificial intelligence with facial recognition.
## :+1:Exercise 1: Connect IoT to AWS Cloud
### Getting Started with Amazon AWS IoT Core using ESP32 
- Hardware: ESP32-2, DHT-11 (Humi-Temp sensor)
- YouTube demo video: https://www.youtube.com/watch?v=idf-gGXvIu4
- Project and source code: https://how2electronics.com/connecting-esp32-to-amazon-aws-iot-core-using-mqtt/
- Also you can download at the top
- ESP32-DHT-11 module pinout: https://esp32io.com/tutorials/esp32-dht11 ![ESP32_DHT-11](https://github.com/iiotntust/1122CFiot/assets/56021651/8e5a4641-ada0-4916-9455-5db77e155f42)
### How to active AWS learn lab
![image](pic/1.png)  
![image](pic/投影片1.JPG)  
> [!CAUTION]
> ### There are something different with the video.
> - Video start from 3:50
> - In the vedio, you can add the policy when you creating things, but now you have to create first.  
> ![image](pic/投影片2.JPG)  
> ### Also setting are change, Fleet indexing
> - There can make yor device connection enable.
> ![image](pic/投影片3.JPG)  
> ### Your end point at MQTT test client
> ![image](pic/投影片4.JPG)  

### Arduino setting
> [!CAUTION]
> CH340 driver: https://www.arduined.eu/ch340-windows-10-driver-download/  
> If you don't have CH340 driver, your Arduino IDE would not recognize your ESP32
> After you open the serial monitor, change the baud rate to 115200 otherwise you cannot see the message from ESP32

-  Put esp32 index into Arduino
-  https://dl.espressif.com/dl/package_esp32_index.json
-  Add esp32 boards from boards manager  
![image](pic/pic1.jpg)  
- Download the library from library manager and add new tab  
![image](pic/pic.jpg)  

- Follow the video create things
- Download the device certificate, private key and CA certificate.
![image](pic/setup.png)
- After your code upload finish, don't forget to press EN bottom, making your esp32 restart
---------------------------------------------------
## :+1:Exercise 2 Alternative: AWS AI Workshop
### 2019 AWS AI Workshop
https://github.com/wimade4u/2019CFiot

## :+1:Exercise 2: Facial recognition (Artificial intelligence) @pending
- The exercise 2 requires IAM func that AWS Academy Account does not support
- May try with AWS Free Tier: https://aws.amazon.com/free/
### Esprissif ESP-EYE + Amazon FreeRTOS
 - AWS document: https://docs.aws.amazon.com/freertos/latest/userguide/freertos-getting-started-modular.html
 - (Stop update) https://github.com/aws/amazon-freertos/blob/main/vendors/espressif/docs/ESP-EYE_getting_started_with_AFR.md
 - The IAM service has limited condition use in the AWS Academy account.
> [!Note]
> 🧱 References for conducting the exercises.
- Arduino IDE download: https://www.arduino.cc/en/software
- Esprissif ESP32 and Ardunio: https://github.com/espressif/arduino-esp32
- Hardware information
  - NodeMCU-32S board: https://docs.ai-thinker.com/en/esp32/boards/nodemcu_32s
  - DFR0620 ESP-EYE Development board: https://www.dfrobot.com/product-1931.html
  - ESP-EYE v2.1: https://github.com/espressif/esp-who/blob/master/docs/en/get-started/ESP-EYE_Getting_Started_Guide.md
  - Free RTOS (Real-time operating system for microcontrollers):[https://freertos.org/index.html](https://freertos.org/index.html)
  - ESP-EYE DevKit with camera and mic
  - ![esp32-esp-eye_inbox_zl](https://github.com/iiotntust/1122CFiot/assets/56021651/42f42532-19b6-4e53-8db9-e9a11a687e6e)

> [!Note]
> ☁️ AWS Cloud Service information.
- AWS Academy login: https://www.awsacademy.com/login
