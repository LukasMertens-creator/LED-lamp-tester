# LED-lamp-tester
Realiseer een schakeling die de lichtopbrengst en de warmte van een LED lamp kan meten gebruik makende van twee digitale sensoren BH1750 (digital lux sensor) en de BMP280 (digital temperature sensor) en een microcontroller naar keuze.  De schakeling geeft beide waardes (lux en celciustemperatuur) weer op een lokaal display alsook op je smartphone.

**English discription:**
In this project we have to make a Led tester, we used 2 kind of sensor's, a BMP280 an a BH1750. We also used a microcontroller, i used a esp32. i have these 2 values are writen on a Oled display. all these componets are connected with I2C. 


![Opstelling](20200312_161345[1].jpg)

**Use pins:**

ESP 32:                                                                                                                 
  pinnen - "Waarvoor gebruikt"                                                                                                                                             
  3V3 - Voeding                                                                                                                           
  Gnd - Ground                                                                                                          
  D22 - SCL                                                                                                                                
  D21 - SDA                                                                                                         
 
DMP280:                                                                                                                                         
  Pinnen sensor - Waar aangesloten                                                                                                                   
  Gnd - Gnd                                                                                                                                
  Vcc - Vcc                                                                                                                        
  SCL - D22                                                                                                                                        
  SDA - D21                                                                                                                        
  CSB - 3V3                                                                                                                   
  SDD - 3V3                                                                                                                   
                                                                                                                     
BH1750:                                                                                                                   
  Pinnen sensor - Waar aangesloten                                                                                                                   
  Vcc - 3V3                                                                                                                   
  Gnd - Gnd                                                                                                                   
  SCL - D22                                                                                                                   
  SDA - D22                                                                                                                   
  Adr - /                                                                                                                   
                                                                                                                     
Oled:                                                                                                                   
  Pinnen sensor - Waar aangesloten                                                                                                                   
  Gnd- Gnd                                                                                                                   
  Vcc - 3v3                                                                                                                   
  SCL - D22                                                                                                                   
  SDA - D21                                                                                                                   
  






