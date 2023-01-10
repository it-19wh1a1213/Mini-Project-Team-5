# Mini-Project-Team-5

Voice Controlled Home Automation using IoT

1) Hardware Devices are : Arduino UNO,Breadboard,Bluetooth Module HC-05,Jumper Wires,220 ohm Resistors,4 LEDs.
2) Firstly, We had build the hardware connections.
Bluetooth Module HC-05                Arduino UNO
              TX ——————————————————————— RX (Pin 0)
              RX ——————————————————————— TX (Pin 1)
              VCC ——————————————–——————— 5v
              GND ——————————————–——————— GND
              
Yellow LED Pin                       Arduino UNO
           Pin 1 ——————————————————————— GND - Breadboard
           Pin 2 ——————————————————————— Pin 9
           
Red LED Pin                          Arduino UNO
           Pin 1 ——————————————————————— GND - Breadboard
           Pin 2 ——————————————————————— Pin 10
           
Orange LED Pin                       Arduino UNO
           Pin 1 ———————————————————————— GND - Breadboard
           Pin 2 ———————————————————————— Pin 11
           
Green LED Pin                        Arduino UNO
           Pin 1 ———————————————————————— GND
           Pin 2 —————————————————————————Pin 12
3) Connect the Bluetooth Module HC - 05 to the Automation app.
-> Open Automation app and allow turning on Bluetooth of the device.
-> Search for Bluetooth device for connection. 
-> To pair with Bluetooth HC-05 module, enter a pin 0000 or 1234.    
-> Select pair device HC-05 to connect with Automation app. 
-> We can control our LEDs with voice commands.
-> We had downloaded latest version of arduino IDE software.
-> We had written the code to control the LEDs by giving the voice commands. 

4)These are the voice commands.
To turn ON the red led - Activate Red LED
To turn ON the yellow led - Activate yellow LED
To turn ON the green led - Activate green LED
To turn ON the orange led - Activate orange LED
To turn OFF the red led - Deactivate red LED
To turn OFF the yellow led - Deactivate yellow LED
To turn OFF the green led - Deactivate green LED
To turn OFF the orange led - Deactivate orange LED
 
5)When we give voice command as ”Activate all” Automation app sends data to Bluetooth module and this data is transmitted from the Bluetooth module to Arduino device and it turn ON all the LEDs. When we give voice command as ”Deactivate all” Automation app sends data to Bluetooth module, and this data is transmitted from the Bluetooth module to Arduino and it turn OFF all the LEDs.
