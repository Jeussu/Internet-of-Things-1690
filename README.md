# Internet-of-Things-1690
Introduction: In this report, I will briefly introduce the definitions of IoT, advantages and disadvantages of the application, followed by an explanation of the tools, hardware needed for IoT machines and machine control language. In addition, I will redefine network protocols and their smaller alternatives, used to connect IoT devices. And finally, the script and the solution to the problem 
	I. 	About IOT: 
1. Definition: 
The internet of things, or IoT, is a collection of interrelated computing devices, mechanical and digital machines, objects, animals or people supplied with unique identifiers (UIDs) and the ability to transmit data across a network without needing human-to-human or human-tocomputer interaction. 
2. Applications in the real world: 
•	Application of the Internet of Things in health care & fitness: Many wearable devices that have flooded the IoT market recently can be roughly classified as health and fitness devices. The Apple, Samsung, Jawbone and Misfit wearables all represent the Internet of Things application. 
Such devices monitor your heart rate, calories, sleep, tracking activity and many other metrics to help us stay healthy. In some cases, such wearable devices can communicate with third-party applications and share information about the user's chronic condition with a healthcare provider. The mobile app paired with the device will send timely notifications to family members or caregivers to notify them when medication is taken or missed. It also provides helpful data on the amount of medication and sends a notification when your medication is about to run out. 
•	Application of the Internet of Things in agriculture: 
- Some of them use a distributed network of smart sensors to monitor various natural conditions, such as humidity, air temperature and soil quality. Others are used to automate irrigation systems. Such an example of IoT devices, Blossom, provides both. This intelligent watering system uses real-time data and weather forecast to create the optimal watering schedule for crops. Including a smart Bluetooth enabled controller and mobile app, this system is easy to install, set up and manage 
3. Pros and cons of IoT:  
-	Communication: IoT encourages communication between devices, also known as Machine-to-Machine (M2M) communication. 
-	Automation helps to better monitor devices: IoT allows you to automate and control the tasks performed daily. Without human intervention, machines can communicate with each other to increase the speed and quality of products. 
-	Information: Clearly having more information helps make better decisions. 
-	Monitors, observed: Advantages of IoT is obvious oversight. It knows exactly the amount of supplies or the quality of air and products in your home and can also provide additional information that you previously had trouble collecting. 
-	Save time: The interaction between the machine gives better efficiency and gives accurate results. 
-	Saving money: The biggest advantage of IoT is saving money, they will alert promptly problems and problems arising. So you can save energy as well as repair costs, maintain multiple products. 
Disadvantages 
-	Compatibility: Because devices from different manufacturers will be interconnected, compatibility issues remain difficult. Currently, there is no international standard for compatibility with devices. to be monitored and supervised 
-	Complexity: IoT is a diverse and complex network, so any errors or bugs in software or hardware can have serious consequences. 
-	Privacy / Security: Our lives will be increasingly controlled by technology, and will depend on it. If all of this IoT data is transmitted, the risk of privacy loss increases. 
 
-	Safety: All home appliances, industrial machinery, public sector services and many other devices are connected to the Internet. Therefore, it created a huge information warehouse available on those devices and this information is vulnerable to attack by hackers. 
4. Architecture: 
![image](https://user-images.githubusercontent.com/94780400/144837258-04bb2195-ada5-4acb-b041-ebf32f9608f9.png)
The above picture is the design of three-tiered architecture, consisting of the bottom, base, and enterprise tiers. Every tier has its own unique roles in managing the data flows and the flows of control involved in the utilization activities. Three networks link you to them (Antonio Grasso, 2018) 
-	The edge consists of the nodes at the bottom. Data is obtained from the nodes at the edge and transmitted through the proximity network. The proximity network links the nodes on the edge to an edge gateway connecting to other networks. Some data collection, processing, and analytics can be done at the edge gateway, depending on the storage and computation power, and it can be used as a management point for the devices and properties. 
-	The application tier is the middle tier of the three-tiered system and deals with the edge tier and business tier respectively using the access network and service network. In addition to demonstrating data-query and analytics capabilities for the edge tier and the enterprise tier, the application tier also handles devices and assets by receiving, storing and forwarding control commands from the enterprise tier to the edge tier. 
-	The application tier is the middle tier of the three-tiered system and deals with the edge tier and business tier respectively using the access network and service network. In addition to demonstrating data-query and analytics capabilities for the edge tier and the enterprise tier, the application tier also handles devices and assets by receiving, storing and forwarding control commands from the enterprise tier to the edge tier. 
5. Framework: 
Before the advent of IoT, most products were rudimentary and physically assembled, but with the development of IoT technology, the application of technology to physical devices was easy and easy. turn them into smart and connected products. The introduction of smart, connected components involves interdisciplinary knowledge, streamlined processes, and features of new technologies. 
Exploring a basic architecture structure for building smart connected products, in this structure, there are 5 separate layers, known as the Intelligent, Connected Product Stack or SCP Stack: 
![image](https://user-images.githubusercontent.com/94780400/144837275-effd20b8-b4fa-4d35-9a8f-bf923208f377.png)
Every one of these layers corresponds to the new components of a smart product linked by: 
-	Sensors Layer: provide a gyroscope that gives the control algorithms orientation information. A camera for visual data delivery. 
-	Connectivity layer: remotely monitor the quad-copter; use radio communication protocol to connect to a Gateway to stream sensor data. 
-	Analytics layer: transform the gyroscope orientation data into motor speeds to optimally change the flight 
-	Smart Apps layer: 2 separate applications: one video display app, and another sensor data control app. 
Therefore, using this method to define intelligent related objects, for example, smart watches are devices that apply IoT technology to track user activity, products that use sensor data to detect user movements, heart rate, etc. ... - Smart watches are part of the SCP stack Consumer Infrastructure layer. 
-	And as part of the sensor layer, there are 3 accelerometers to monitor motion, which equate the user's wrist movement with the number of steps taken 
-	for users to monitor information and status when using a smart watch, the device uses Bluetooth connectivity to transfer data between the phone and the product. It is part of the authentication layer 
-	As part of the Analytics framework, the smart watches receive feedback through the Smart App, the final framework of the SCP stack, based on the user's personal goals and activity patterns. You can access this information through the smart watches app on the user's smartphone, or via a web browser 
6. Tools 
There are two microcontroller modules, Arduino and Raspberry Pi, which play a key role within the IoT network. Arduino is a microcontroller circuit, a pure part of Raspberry pi, whereas Raspberry pi is a mini-computer. Raspberry Pi is perfect for software applications because of Arduino simplifies hardware projects. Here are the variations between the two instruments. 
![image](https://user-images.githubusercontent.com/94780400/144837392-c026578c-ed26-4456-a71d-e0de1ea8d4af.png)
7.  	Hardware: 
Hardware in the IOT are the sensors and actuators: 
 Sensor: 
•	A sensor is a device that detects the physical environment and responds to some type of input. 
•	The basic input may be light, wind, motion, humidity, pressure, or any of the many other environmental phenomena. 
•	Normally, the output is a signal that is transformed into a human-readable display at the position of the sensor or transmitted electronically over a network for reading or processing. 
Actuators: 
•	An actuator is a system that moves any process or controls it. An actuator converts a control signal into mechanical motion, like an electric motor. Actuators may be based on hydraulic, pneumatic, electrical, thermal or mechanical devices but are increasingly software powered 
8. Software: 
There are programming languages for the applications such as Assembly, C, B #, 
C++, To, Java, JavaScript, Parasail, PHP, Python, Rust, Swift 
![image](https://user-images.githubusercontent.com/94780400/144837424-b3fc661c-f440-46e7-aef0-2353ac45d44f.png)
-	Some programming languages, such as C, are very good at creating quick-torun code which makes effective use of the machine. 
-	But the efficacy comes at a cost. Many C programs are not portable – that means writing a program for one computer doesn't allow you to use the program on another computer easily. 
-	We might consider Java if we want a portable file. This language is very mobile. As a rule, Java code written on one machine can be used on any other machine as well. 
-	However, Java is not as powerful as C and allows Java to operate on the machine which is attempting to run the Java program. Which means it will take up more money, too.  
-	Some languages have fairly limited functions, but that does mean they do a few things very well in general. R's great at visualization, for starters.  
-	In comparison, Python is great at organizing vast quantities of data. 
9. IOT Network/ Internet protocols:  
A. Internet Protocol: 
-	The addresses used to transmit data in networks are called addresses of the Internet Protocol (IP). Ipv4 (version 4) is what's actually usually in use. 
-	Ipv4 addresses consist of four sets of period-separated numbers, with each number between 0-255. 
-	For example:  1.2.3.4 or 233.67.151.3  
-	Ipv6 is being built using six sets of numbers, colon numbers, and hexadecimal numbers to allow many more addresses of destinations. It will help promote IoT and incorporate functionality for improved routing, security and data flow. 
-	Ipv4 has around 4 billion IP addresses (which ran out a few years back.) Ipv6 (128 bits) has around 340 undecillion IP addresses - that's 
340,000,000,000,000,000,000,000,000 give or take a few billion. 
B. MAC Address: 
-	A device's MAC address is a unique identifier that is assigned to network interface controllers 
-	It can also be called the hardware address, or physical address. 
-	Many modern IEEE 802 network technologies, such as Ethernet, Wi-Fi, and Bluetooth, use that address. 
-	48 bytes, 12 hexadecimal integers, displayed in different formats.  
-	Usually tied to a device 
-	Have two parts: the manufacturer UOI, and the device ID portion 
-	Generally, set addresses, and not configured by the user 
-	The standard (IEEE 802) format for human-friendly printing of the MAC-48 addresses is six groups of two hexadecimal digits, separated by hyphens (-); 
C. Domain Name System: 
-	Domain Name Service or DNS which is a telephone book similar to the Internet. It matches a name (like facebook.com) to a number (like 157.240.8.35)because humans like to manage names and like numbers to computers. 
-	The DNS is a huge machine name database and its internet addresses but it is spread out so that no server has all the details. 
-	When a device requests a domain name, and that server does not have it, the request will be forwarded to another DNS server. There is a hierarchical structure in the Domain Name Service, and requests are sent from bottom up. 
![image](https://user-images.githubusercontent.com/94780400/144837454-c9720642-eb82-4e90-b96b-66a3e95b694b.png)
D. Wi-Fi: 
-	Wi-Fi refers to the radio frequency (RF) category of protocols used to transmit data over a Wireless Local Area Network (WLAN). 
-	Wi-Fi operates at the unlicensed RF frequency frequencies between 2.4 and 5 Gigahertz (GHz). 
![image](https://user-images.githubusercontent.com/94780400/144837477-061a6393-061e-47f8-8ce6-3a7c32400ee6.png)
E. Bluetooth: 
-	Bluetooth is a low-power, short-range (typically less than 10 m up to 100 m). It allows mobile devices to attach to each other with minimal setup and wireless accessories. 
-	Bluetooth Low Energy (BLE) is used for applications in education, wellness, beacons, protection, and home entertainment. 
F. NFC: 
-	Near-field communication (NFC) is a series of communication protocols that allow two electronic devices-usually portable devices, such as smartphones-to create low-speed communication by bringing them within 4 cm of each other. 
-	NFC devices, including those used on credit cards and electronic ticket smartcards, are used in contactless payment systems. The NFC-enabled devices will serve as documents and keycards for electronic identification. 
G. TCP/IP model (Protocol): 
- The layered TCP / IP (Transport Control Protocol / Internet Protocol) model follows the OSI model's partitioning and abstraction concepts, as applied to a particular suite of protocols.  
![image](https://user-images.githubusercontent.com/94780400/144837497-ee710927-85fd-449d-b418-3694af6610b5.png)
![image](https://user-images.githubusercontent.com/94780400/144837505-92ebf7e0-ca22-49ee-a8e3-409ad6d738cd.png)
![image](https://user-images.githubusercontent.com/94780400/144837522-bc12b89f-0262-4334-93d1-32205a5ee439.png)
I. Application protocol: 
-	The network protocols like HTTP and XMPP, which are typically found in the Server layer. However, these are not an acceptable choice for communication with a large number of connected devices in an IoT-constrained environment. Therefore, the IoT industry needs more lightweight protocols to address this issue. 
-	The two most common IoT application protocols [Hanes et al 2017] are the Constrained Application Protocol (CoAP) and the Message Queuing Telemetry Transport (MQTT). 
-	CoAP is based on the HTTP protocol and was conceived by the working group of IETF Restricted RESTful Environment (CoRE). 
-	Message Queuing Telemetry Transport (MQTT) is a lightweight protocol ideally tailored to restricted environments-for example, a harsh environment with a limited bandwidth link, for example in the oil and gas industries. 
Here are the reasons why IoT devices will use CoAP rather than HTTP: 
![image](https://user-images.githubusercontent.com/94780400/144837550-fbc5849e-ab69-4bc6-be6e-817e9ac4c024.png)
That's MQTT architecture: 
![image](https://user-images.githubusercontent.com/94780400/144837568-b02e1197-44d6-45a1-8857-3e46c3a4f65a.png)
J. Network / Internet Layer: 
- IPv6 addresses are too long for IoT data frames and methods; it includes specifications and protocols to encapsulate the IPv6 datagram into small packages. The first protocol to successfully encapsulate IPv6 over Low Power Wireless Personal Network (6LoWPAN) 
K. Scenario for an IOT solution: 
1. The scenario: 
• technology in the 21st century is changing and evolving and everything is automated with just a tap of a smartphone over a network connection, for this scenario I will create a throne Smart home, an automatic home sitting can: 
-	when I get home from work, I can use my smartphone to open the door 
-	The system can recognize gestures and automatically turn on the lights when I enter the door 
-	The fan has an intelligent system that adjusts the temperature depending on the outside temperature and weather and the AC will be turned on 
-	Car garage automatically closes and opens by me when I using smartphone 
2. Requirements and the solution 
-	I will use a motion sensor to detect movement, a temperature sensor to detect temperature, then an IoT door, windows, LED light, AC The most important thing is the home gateway, which is the center of all IoT apps, and a smartphone to connect, the home gateway's default account is admin and admin. 
-	Once I enter a room, the motion sensor on the ceiling will detect me and switch on the lights in which I am, and switch off when the motion sensor detects no motions 
-	The same applies to the garage door, where it is connected to the home gateway and can only be opened and closed manually or via smartphone 
 
 
 
References 
Antonio 	Grasso, 	2018. 	IIC: 	Industrial 	IoT 	Reference 	Architecture. 	[Online]  Available 	at: 	http://iiot-world.com/connected-industry/iic-industrial-iot-referencearchitecture/?utm_content=buffer43f5f&utm_medium=social&utm_source=twitter.com&utm_cam paign=buffer 
