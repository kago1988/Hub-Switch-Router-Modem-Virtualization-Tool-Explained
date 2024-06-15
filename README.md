# Network Devices Overview

## Hub
A hub is a network device that broadcasts information to every device on the network.

![Hub](Hub/Hub.jpg)

### When to Use:
- **MAC Address:** Hubs operate at the data link layer (Layer 2) and use MAC addresses to identify devices on the network.

## Switch
A switch is a network device that makes connections between specific devices on a network by sending and receiving data between them. Switches are more intelligent than hubs since they only pass data to the intended destination. This makes them more secure than hubs.

![Switch](Switch/Switch.jpg)

### When to Use:
- **MAC Address:** Switches also operate at the data link layer (Layer 2) and use MAC addresses to direct data to the correct device on the local network.

## Router
A router is a network device that connects multiple networks together. If a computer wants to send information to a computer on another network, then:
![Router](Router/Router1.jpg)
1. The information travels from the computer to the router.
![Router](Router/Router2.jpg)
2. The router reads the destination address and forwards the data to the intended network router.
![Router](Router/Router3.jpg)
3. Finally, the receiving router directs that information to the destination PC.

### When to Use:
- **IP Address:** Routers operate at the network layer (Layer 3) and use IP addresses to route data between different networks. When accessing a website or sending data over the internet, IP addresses are used to determine the data's path.

## Modem
A modem is a device that connects your router to the internet and brings internet access to the LAN. The process is as follows:
![Modem](Modem/Modem1.jpg)
1. The computer sends information to the router.
![Modem](Modem/Modem2.jpg)
2. The router transports the information through the modem
![Modem](Modem/Modem3.jpg)
3. to the internet.
![Modem](Modem/Modem4.jpg)
4. The intended recipient modem receives the information
![Modem](Modem/Modem5.jpg)
5. and transports it to the intended router.
![Modem](Modem/Modem6.jpg)
6. Finally, the receiving router directs that information to the destination PC.

### When to Use:
- **IP Address:** Modems work with routers to provide internet access, using IP addresses to communicate with other devices on the internet.

## Virtualization Tools
Virtualization tools are software that perform network operations.

- Virtualization tools carry out functions that would normally be completed by a hub, switch, router, or modem.
- They are often provided by cloud providers.
- These tools provide opportunities for cost savings and scalability.

### When to Use:
- **IP Address & MAC Address:** Virtualization tools often simulate the functions of physical network devices, using both IP and MAC addresses to manage and route data in virtual environments.



## Further terms 

Bandwidth: The maximum data transmission capacity over a network, measured by bits per second

Cloud computing: The practice of using remote servers, application, and network services that are hosted on the internet instead of on local physical devices

Cloud network: A collection of servers or computers that stores resources and data in remote data centers that can be accessed via the internet

Data packet: A basic unit of information that travels from one device to another within a network

Hub: A network device that broadcasts information to every device on the network

Internet Protocol (IP): A set of standards used for routing and addressing data packets as they travel between devices on a network

Internet Protocol (IP) address: A unique string of characters that identifies the location of a device on the internet

Local Area Network (LAN): A network that spans small areas like an office building, a school, or a home

Media Access Control (MAC) address: A unique alphanumeric identifier that is assigned to each physical device on a network

Modem: A device that connects your router to the internet and brings internet access to the LAN

Network: A group of connected devices

Open systems interconnection (OSI) model: A standardized concept that describes the seven layers computers use to communicate and send data over the network

Packet sniffing: The practice of capturing and inspecting data packets across a network

Port: A software-based location that organizes the sending and receiving of data between devices on a network

Router: A network device that connects multiple networks together

Speed: The rate at which a device sends and receives data, measured by bits per second

Switch: A device that makes connections between specific devices on a network by sending and receiving data between them

TCP/IP model: A framework used to visualize how data is organized and transmitted across a network

Transmission Control Protocol (TCP): An internet communication protocol that allows two devices to form a connection and stream data

User Datagram Protocol (UDP): A connectionless protocol that does not establish a connection between devices before transmissions

Wide Area Network (WAN): A network that spans a large geographic area like a city, state, or country

Address Resolution Protocol (ARP): A network protocol used to determine the MAC address of the next router or device on the path

Cloud-based firewalls: Software firewalls that are hosted by the cloud service provider

Controlled zone: A subnet that protects the internal network from the uncontrolled zone

Domain Name System (DNS): A networking protocol that translates internet domain names into IP addresses

Encapsulation: A process performed by a VPN service that protects your data by wrapping sensitive data in other data packets

Firewall: A network security device that monitors traffic to or from your network

Forward proxy server: A server that regulates and restricts a person’s access to the internet

Hypertext Transfer Protocol (HTTP): An application layer protocol that provides a method of communication between clients and website servers

Hypertext Transfer Protocol Secure (HTTPS): A network protocol that provides a secure method of communication between clients and servers

IEEE 802.11 (Wi-Fi): A set of standards that define communication for wireless LANs

Network protocols: A set of rules used by two or more devices on a network to describe the order of delivery of data and the structure of data

Network segmentation: A security technique that divides the network into segments

Port filtering: A firewall function that blocks or allows certain port numbers to limit unwanted communication

Proxy server: A server that fulfills the requests of its clients by forwarding them to other servers

Reverse proxy server: A server that regulates and restricts the internet's access to an internal server

Secure File Transfer Protocol (SFTP): A secure protocol used to transfer files from one device to another over a network

Secure shell (SSH): A security protocol used to create a shell with a remote system 

Security zone: A segment of a company’s network that protects the internal network from the internet

Simple Network Management Protocol (SNMP): A network protocol used for monitoring and managing devices on a network

Stateful: A class of firewall that keeps track of information passing through it and proactively filters out threats 

Stateless: A class of firewall that operates based on predefined rules and does not keep track of information from data packets

Subnetting: The subdivision of a network into logical groups called subnets

Transmission Control Protocol (TCP): An internet communication protocol that allows two devices to form a connection and stream data

Uncontrolled zone: The portion of the network outside the organization

Virtual private network (VPN): A network security service that changes your public IP address and masks your virtual location so that you can keep your data private when you are using a public network like the internet

Wi-Fi Protected Access (WPA): A wireless security protocol for devices to connect to the internet

Active packet sniffing: A type of attack where data packets are manipulated in transit

Botnet: A collection of computers infected by malware that are under the control of a single threat actor, known as the “bot-herder"

Denial of service (DoS) attack: An attack that targets a network or server and floods it with network traffic

Distributed denial of service (DDoS) attack: A type of denial of service attack that uses multiple devices or servers located in different locations to flood the target network with unwanted traffic

Internet Control Message Protocol (ICMP): An internet protocol used by devices to tell each other about data transmission errors across the network

Internet Control Message Protocol (ICMP) flood: A type of DoS attack performed by an attacker repeatedly sending ICMP request packets to a network server

IP spoofing: A network attack performed when an attacker changes the source IP of a data packet to impersonate an authorized system and gain access to a network

On-path attack: An attack where a malicious actor places themselves in the middle of an authorized connection and intercepts or alters the data in transit

Packet sniffing: The practice of capturing and inspecting data packets across a network 

Passive packet sniffing: A type of attack where a malicious actor connects to a network hub and looks at all traffic on the network

Ping of death: A type of DoS attack caused when a hacker pings a system by sending it an oversized ICMP packet that is bigger than 64KB

Replay attack: A network attack performed when a malicious actor intercepts a data packet in transit and delays it or repeats it at another time

Smurf attack: A network attack performed when an attacker sniffs an authorized user’s IP address and floods it with ICMP packets

Synchronize (SYN) flood attack: A type of DoS attack that simulates a TCP/IP connection and floods a server with SYN packets

Baseline configuration (baseline image): A documented set of specifications within a system that is used as a basis for future builds, releases, and updates

Hardware: The physical components of a computer

Multi-factor authentication (MFA): A security measure which requires a user to verify their identity in two or more ways to access a system or network

Network log analysis: The process of examining network logs to identify events of interest 

Operating system (OS): The interface between computer hardware and the user

Patch update: A software and operating system update that addresses security vulnerabilities within a program or product

Penetration testing (pen test): A simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes 

Security hardening: The process of strengthening a system to reduce its vulnerabilities and attack surface

Security information and event management (SIEM): An application that collects and analyzes log data to monitor critical activities for an organization

World-writable file: A file that can be altered by anyone in the world