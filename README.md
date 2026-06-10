# TRYHACKME-Intro-to-LAN-part-1
Local Area Network(LAN) Topologies: Since the inception of the internet there has been various testing &amp; executions of LAN(local Area Network)/ Network designs of connecting devices to the internet in regards to networking the use of the term topology is used in reference to the design of the network connecting devices to the internet &amp; or server. 

## Star Topology
TryHackMe Room Intro to LAN
Technologies and designs that power private Networks.

Local Area Network(LAN) Topologies:
Since the inception of the internet there has been various testing of executions of LAN(local Area Network)/ Network designs of connecting devices to the internet in regards to networking the use of the term topology is used in reference to the design or look of the network connecting devices to the internet and or server. 

Star Topology 
Now the most commonly used Topology for LAN/ connecting devices to a local network is the Star Topology. Devices are individually connected via central networking devices, i.e. switch or hub. For everyday customers/users are connect to hub for example the Sky Hub or BT Hub, these are the central point for your home network/ local Area Network(LAN). These are the most common because of reliability and scalability. 


<img width="463" height="393" alt="image" src="https://github.com/user-attachments/assets/c9d236da-87f8-4ac9-89fb-6a370cc07801" />


Advantages: 
•	Scalability( adding devices) with ease.
•	Can be replaced with ease for smaller scale networks(home users and small businesses).
•	Easy Troubling and Management, because all devices link to 
a central point, if for example port 4 on the bub isn’t connecting 
you know what device or cable is at fault. 
•	Importantly Security and Upgrades: since all traffic(data) pass through the central hub/switch it is easier for SOC Analyst/ Blue Teamers/network administrators to monitor traffic(data coming in and out of devices & internet), with SIEM (Security Information and Event Management)or an IDS/IPS (Intrusion Detection/Prevention System)install firewalls and manage network policies. 


Disadvantages: 
•	If the centralised device(hub or switch) fails/ breaks,
the connected devices cant receive or send data. 
•	Larger Networks i.e. organisation(s) that are inherently 
Scaling, often need more maintenance, which can and does effect the CIA Triad(Confidentiality, Integrity &, Availability)especially Availability of systems and networks for users & employees.
•	In the realm of Cyber Security there is a Confidentiality & Integrity Risk of the CIA Triad, all data that converges at one central point, the switch becomes a high value target, if a Hacker manages to compromise or connect to the switch/LAN, they can alter data on every device on the network and gain network administrative privileges. 
