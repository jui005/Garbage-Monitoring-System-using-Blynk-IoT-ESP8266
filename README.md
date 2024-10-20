Overview of the Smart Dustbin Project:
The Smart Dustbin is an innovative project designed to enhance waste management by incorporating IoT technology. It consists of several components working together to monitor the bin’s status and provide remote access through the Blynk web server. Here's a breakdown of the system:

Garbage Level Monitoring:
An ultrasonic sensor is used inside the dustbin to measure the level of garbage. The sensor continuously tracks the distance between the lid and the top layer of waste, determining how full the dustbin is.
Once the garbage reaches a certain level, an alert or notification can be sent to notify the concerned party that the dustbin needs to be emptied.



Human Detection:
An IR sensor is attached outside the dustbin to detect the presence of a human or object near the bin.
When someone approaches, the IR sensor triggers the system to open the dustbin lid, ensuring contactless waste disposal.




Servo Motor-Controlled Lid:
The servo motor is responsible for opening and closing the dustbin lid. Upon detecting a nearby human via the IR sensor, the servo motor is activated, automatically lifting the lid.
After a predefined duration, the lid closes automatically, enhancing hygiene and reducing direct contact.



Monitoring via Blynk Web Server:
The project is integrated with the Blynk web server, providing real-time monitoring of the dustbin’s status remotely. Through the Blynk app or web interface, users can:
Monitor the garbage level.
Track the location of the dustbin, especially useful in public or large areas.
Receive notifications when the bin is full or when there’s a fault in the system.





Project Functionality:
This smart dustbin offers contactless waste management by utilizing sensors and servo motors.
The IoT connectivity via the Blynk platform allows for efficient tracking and monitoring, making it suitable for smart cities, public places, and homes.
