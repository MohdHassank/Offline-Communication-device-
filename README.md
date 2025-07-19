# Offline-Communication-device-



Problem statement 

In remote, disaster-prone, or rural areas with limited or no internet connectivity, communication becomes nearly impossible, especially during emergencies. Our project addresses the lack of reliable offline communication systems by enabling device-to-device messaging without cellular networks or Wi-Fi.


Approach and Solution 

In disaster-prone or remote areas, traditional communication systems often fail due to the unavailability of mobile networks or internet services. Our solution is a compact and cost-effective Offline Communication Device that enables text-based communication without any network or SIM card.
The device works using LoRa (Long Range Radio) technology integrated with Arduino Nano microcontrollers, allowing users to send and receive messages over several kilometers. It connects to an Android phone via OTG cable, opening a our developed app named LoRaMesh for chatting.
When two or more such devices are in range, they automatically detect each other and allow users to select a contact to initiate a chat. 
This innovation ensures reliable peer-to-peer communication, even when infrastructure is completely down, providing a lifeline in emergency situations.


 Features:

1-Works Without Internet or SIM: Enables messaging in areas with no connectivity

2-Long-Range Communication: Up to 5 km range using LoRa technology

3-USB-OTG Based Phone Connectivity: Easy plug-and-play setup on Android

4-Peer-to-Peer Chat Interface: Send and receive messages between devices

5-Low Power Consumption: Ideal for field use during power outages

6-Secure & Private: No dependency on centralized servers or cloud


Technology Stack:

1- Hardware:

      Arduino Nano – Controls the communication logic

      Reyax RYLR998 LoRa Modules – Enables long-range wireless messaging

      Resistors (4.7kΩ and 10kΩ) – Used for voltage regulation and safety

      OTG Cable – Connects Arduino to Android phone

      3D Printed Enclosure – Compact protective casing

2- Software:

      Arduino IDE – For coding and uploading logic to microcontroller

      Mobile USB Serial Library – Enables OTG-based communication



Run Instructions
1. Flash Arduino code to Nano using Arduino IDE.
2. Connect LoRa module as per wiring diagram.
3. Power the device (USB or battery).
4. Use USB-OTG to connect the device to Android phone.
5. Open Serial USB Terminal app and set baud rate to 9600.
6. Start chatting between two devices.
   (Each person needs their own phone + device.)


