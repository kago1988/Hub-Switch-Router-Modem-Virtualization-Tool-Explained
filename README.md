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
