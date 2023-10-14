# MQTT_Prj
Lập trình hệ thống theo dõi chuyển động giao tiếp bằng mạng MQTT
  - Môi trường lập trình: AduinoIDE, MIT App Invertor.
  - Phần cứng: ESP8266, cảm biến hồng ngoại PIR HC-SR501.
  - Chức năng:
     (+) Phần cứng: MCU nhận tín hiệu báo chuyển động từ cảm biến và gửi thông tin lên MQTT Broker (xây dựng trên nền tảng của Mosquitto).
     (+) App: Kết nối và nhận data từ Broker thông qua các topic, hiển thị số lượng và thời điểm phát hiện chuyển động. 
  - Link video demo: https://drive.google.com/file/d/1l_mE9iAQeLW2if9jcgnYYISF8BpjoGog/view?usp=sharing
