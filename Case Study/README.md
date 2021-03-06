# **SMART WATCH**

## INTRODUCTION
Smart watches present a unique set of challenges when it comes to design. They offer a feature-set that goes far beyond what is found in traditional watches but come with expectations of a similar form factor.The features offered by the latest smart watches include application and notification syncing with a smartphone, fitness and health monitoring, location service, voice commands and wireless charging.


## REQUIREMENTS 
 - High Level Requirements

   |HLR_ID|High level requirements|
   ---|---|
   |HLR01| Accuracy of the sensors|
   |HLR02| How fast the controller receives data|
   |HLR03| Connectivity Testing|
   |HLR04| How well the display can show the received data|

- Low Level Requirements

   |LLR_ID|Low level requirements| 
   ---|---|
   |LLR01_HLR01|It shall have Pulse sensor to detect the blood pulse|
   |LLR02_HLR01|It shall have Temperature sensor to measure the temperature|
   |LLR03_HLR01|It shall have Accelerometer sensor to measure the static force|
   |LLR04_HLR01|It shall have Step counter sensor to count our Activity|
   |LLR05_HLR01|It shall have Humidity sensor to detect humidity|
   |LLR06_HLR02|It shall have Microcontroller |
   |LLR07_HLR03|It shall have Bluetooth Module to connect mobile|
   |LLR08_HLR03|It shall have RFID reader to detect the device|
   |LLR09_HLR03|It shall have Real Time clock|
   |LLR10_HLR03|It shall have Near Field Technology to connect fast|
   |LLR11_HLR04|It shall have Display to display the screen|
   |LLR12_HLR04|It shall have Motor for vibration|
   

## SYSTEM DESIGN
   
   ![Smart watch](https://user-images.githubusercontent.com/82401251/154804772-110aa88e-ae3d-4ea2-b2d7-4268439431b3.jpg)



## SUB-SYSTEM DESIGN
   
- ###### Pulse sensor
![Pulse sensor](https://user-images.githubusercontent.com/82401251/154805019-95da554f-2f97-47f2-a94d-bd501b355885.jpg)

- ###### Temperature sensor
![Temperature sensor](https://user-images.githubusercontent.com/82401251/154805033-d7886a91-5b5f-4724-8d3b-3712fea39b9b.jpg)

- ###### Accelerometer Sensor
![Accelerometer sensor](https://user-images.githubusercontent.com/82401251/154805041-b6eba80f-51b1-4d69-a9d7-5e959d14a451.jpg)

- ###### Humidity Sensor
![Humidity sensor](https://user-images.githubusercontent.com/82401251/154805056-71397a01-7c93-4fbb-bed7-f0dba4a73682.jpg)

- ###### Bluetooth Module
![Bluetooth solution-Page-3](https://user-images.githubusercontent.com/82401251/154805421-531f13c2-5f71-4cc1-8db0-66cf73451c4a.jpg)

- ###### RFID Reader
![RFID](https://user-images.githubusercontent.com/82401251/154805540-d4006ef8-678d-4b62-b734-fa2b3e82eadf.jpg)

- ###### NFC (Near Field Technology)
![NFC](https://user-images.githubusercontent.com/82401251/154805550-4f2a9c09-aab4-42af-9aa2-3417b8f512c5.jpg)

- ###### RTC (Real Time Clock)
![Real Time Clock](https://user-images.githubusercontent.com/82401251/154805572-7c1831fc-5772-465c-bfa2-bd1a3c50e8a1.jpg)

- ###### Power Management Unit
![power supply unit-Page-2](https://user-images.githubusercontent.com/82401251/154805585-dc799de7-c373-4e6d-8db4-7b9818337ed2.jpg)

- ###### Vibration Motor
![Vibration Motor](https://user-images.githubusercontent.com/82401251/154805592-204b8e89-43da-4205-9ffb-527ecc3032f9.jpg)

- ###### Display
![Bluetooth solution-Page-4](https://user-images.githubusercontent.com/82401251/154805595-9289ff54-0a6d-493c-9c94-bc0e085c3bfc.jpg)



## Components Description
  
* ###### Microcontroller
An integrated circuit that contains a microprocessor along with memory and associated circuits and those controls some or all the functions of an electronic device (such as a home appliance) or system.

* ###### Bluetooth
Bluetooth is an open wireless technology standard for transmitting fixed and mobile electronic device data over short distances.

* ###### RFID Reader
An RFID reader is a radio frequency device that emits a signal through an antenna. This signal is received by RFID tags that respond to interrogation by the reader. Responses are read by the reader, and through a variety of protocols the reader can communicate with all the RFID tags in its field.

* ###### NFC (Near Field Communication)
NFC is a short-range high frequency wireless communication technology that enables the exchange of data between devices over about a 10 cm distance.

* ###### DAC
Digital-to-Analog Converter (DAC) is a device for converting Digital signals into corresponding Analog signals.

* ###### ADC
Analog-to-Digital Converter (ADC) is a device for converting Analog signals into corresponding Digital signals.

* ###### Vibration motor
Vibration motor is a coreless DC motor, and the size of this motor is compact. The main purpose of this motor is to alert the user from receiving the call by without sound/vibrating. These motors are applicable for different applications like pagers, handsets, cell phones, etc.

* ###### LCD
LCD (Liquid Crystal Display) is a type of flat panel display which uses liquid crystals in its primary form of operation. LEDs have a large and varying set of use cases for consumers and businesses, as they can be commonly found in smartphones, televisions, computer monitors and instrument panels.

* ###### Real Time Clock
A real-time clock (RTC) is a battery-powered clock that is included in a microchip in a computer motherboard.

* ###### Memory
Memory is an important part of embedded systems. The cost and performance of an embedded system heavily depends on the kind of memory devices it utilizes.

* ###### RAM
Random access memory (RAM) is a computer's short-term memory, which it uses to handle all active tasks and apps. It is a hardware device generally located on the motherboard of a computer and acts as an internal memory of the CPU. 

* ###### EEPROM
EEPROM stands for electrically erasable programmable read-only memory and is a type of non-volatile memory used in computers, integrated in microcontrollers for smart cards and remote keyless systems, and other electronic devices to store relatively small amounts of data by allowing individual bytes to be erased and reprogrammed.

* ###### Power Management Unit
The PMU is a microcontroller, or integrated circuit, that controls the power functions of Macintosh computers. Though it is not a large component, the PMU contains several parts, including memory, software, firmware, and its own CPU. 

* ###### Pulse Sensor
A pulse wave is the change in the volume of a blood vessel that occurs when the heart pumps blood, and a detector that monitors this volume change is called a pulse sensor.

* ###### Temperature Sensor
A temperature sensor is a device that is designed to measure the degree of hotness or coolness in an object. The working of a temperature meter depends upon the voltage across the diode.

* ###### Pressure Sensor
A pressure sensor is an instrument consisting of a pressure sensitive element to determine the actual pressure applied to the sensor and some components to convert this information into an output signal.

* ###### Accelerometer Sensor
An accelerometer is an electromechanical device that is used to measure acceleration forces. Such forces may be static like the force of gravity or, they may be dynamic as in the case of mobile devices.

* ###### Step Counter Sensor
The step counter sensor provides the number of steps taken by the user since the last reboot while the sensor was activated.

* ###### Humidity sensor
Humidity sensors are electronic devices enabling you to measure the environment???s humidity and convert the data into a corresponding electrical signal that can be used for different purposes.



## SUB-SYSTEM TESTING

|Test_ID|Sub-System Test Cases|
---|---|
|TC01|Check the functionality of the on/off button.|
|TC02|Check Pulse sensor can detect the blood flow, pulse rate.|
|TC03|Check Temperature sensor in different body conditions.|
|TC04|Check Accelerometer sensor can detect moving position, rest position.|
|TC05|Check Step count sensor can detect steps (Walk, Run, Cycling).|
|TC06|Check Humidity sensor in different climate change (Moisture, Dry).|
|TC07|Check Smartwatch connects with your mobile or not.|
|TC08|Check Bluetooth device range when it is highly covered.|
|TC09|Check Bluetooth device range when it is partially covered.|
|TC10|Check RFID Tag is being detected by device.|
|TC11|Check NFC range and accurate it connects.|
|TC12|Check RTC for tracking the current date and time.|
|TC13|Check Alarm function is working fine or not.|
|TC14|Check Power Management unit status for high power.|
|TC15|Check Power Management unit status for low powe.|
|TC16|Check Battery is chargeable or not.|
|TC17|Check the time of a Power cell works in the watch.|
|TC18|Check Vibration motor when turned ON/OFF.|
|TC19|Check vibration motor when some notifications.|
|TC20|Check if the display isn???t too bright or too dark.|
|TC21|Check the information displayed in the display panel is correct.|
|TC22|Check effect of water and oil and other liquid on Display.|
  


## SYSTEM TESTING

|TEST_ID| System Test cases|
---|---|
|TC01| Check how sensors work accurately.|
|TC02| Check how fast the Micro controller receives data.|
|TC03| Check the Bluetooth, NFC, RFID connectivity.|
|TC04| Check how well the display can show the received data.|



## Applications

- Time-related features
- Smart features
- Health management
- Navigation
- Notifications
- Fashionable



## References

- [Wikipedia](https://en.wikipedia.org/wiki/Smartwatch)
- [IEEE](https://ieeexplore.ieee.org/document/8123790)
