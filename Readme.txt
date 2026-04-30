Tampilan Menu perangkat IoT monitoring fasilitas penunjang v1.1 AirNav Surabaya

sumber referensi:
1. https://www.youtube.com/watch?v=ak5TsUFhyf8&t=241s
2. https://randomnerdtutorials.com/esp32-ssd1306-oled-display-arduino-ide/
3. https://www.upesy.com/blogs/tutorials/rotary-encoder-esp32-with-arduino-code
4. https://randomnerdtutorials.com/esp32-dht11-dht22-temperature-humidity-sensor-arduino-ide/
5. https://indobot.co.id/blog/membaca-input-dari-sensor-getar-vibration-sensor/
6. https://projecthub.arduino.cc/yilmazyurdakul/arduino-oled-encoder-simple-menu-system-e998b8

config pin:
1. Oled
   sda = pin 21
   sck = pin 22
   vcc = 3.3v
   gnd = gnd 

2. Rotary encoder
   CLK = pin 18
   DT  = pin 19
   SW  = pin 23
   vcc = 3.3v
   gnd = gnd
	
3. Sensor Getaran
   DO = pin 15
   vcc = 3.3v
   gnd = gnd 

4. DHT sensor
   out = pin 4
   vcc = 3.3v
   gnd = gnd 

5. LED
   green = pin 16
   yellow = pin 17
   red = pin 5
   gnd = gnd

How To Open flowchart file:
go to https://app.diagrams.net/
choose file > Open from > Device > flowcartMenu.dio