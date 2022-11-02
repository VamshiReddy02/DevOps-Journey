## Client Server Architecture

Before we explain client server architecture and you start reading words such as servers, service, network, data, and files, and start feeling overwhelmed with jargon, let us first understand about this architecture in layperson’s terms.

The notion of client-server architecture can be understood by the analogy of ordering a pizza for delivery. You call the store to order a pizza and someone picks up the call, takes your order, and then delivers it. Simple, right? Yes, this analogy pretty much answers the fundamental principle of client server architecture.

Client server architecture is a computing model in which the server hosts, delivers, and manages most of the resources and services requested by the client. It is also known as the networking computing model or client server network as all requests and services are delivered over a network. The client-server architecture or model has other systems connected over a network where resources are shared among the different computers.

Typically, client server architecture is arranged in a way that clients are often situated at workstations or on personal computers, while servers are located elsewhere on the network, usually on more powerful machines. Such a model is especially beneficial when the clients and server perform routine tasks. For example, in hospital data processing, a client computer can be busy running an application program for entering patient information, meanwhile the server computer can be running another program to fetch and  manage the database in which the information is permanently stored.

## Networking Devices

There are lots of devices which are use to communicate with devices these devices called Networking Devices,There Internal,External or Portable Devices , Internal basically in side the desktop,laptop or mobile like ethernet wifi card or bluetooth if we disconnect our device it does not effect other device until its not in shared devices , External Devices is shared devices every person in a network is using that devices , not directly but indirectly every devices has its importance in a network,Portable Devices battery power device which help to create own network for few hours, using mobile you can create hotspot and allow yours internet share other mobile devices.


### Internal Devices

● Network interface controller (NIC)
● Wireless Network Interface Controller
● Bluetooth Dongle

### External Devices

● Hub
● Switches
● Routers
● Brouters
● Bridges
● Repeater
● Modem
● Gateway
● WIFI-Routers or Broadband Routers


### Gateway

A gateway is not a hardware devices its self , its is software firmware which save configuration setting of a device mostly the gateway address in routers is 192.168.0.1 or 192.168.1.1.
Its acts as a “gate” between two networks. It may be a router, firewall, server, or other device that enables traffic to flow in and out of the network. While a gateway protects the nodes within network, it also a node itself.

### Repeater

Repeater is use to extend the range of radio signal so that the signal can cover longer distances, a repeater is an electronic device that receives a signal and re transmits it.Repeater is used for wired medium (e.g. telephone line repeater, fiber optical cable repeater etc.) as well as wireless medium (e.g. satellite repeater, microwave repeater, wifi repeater, LTE repeater etc.).
Types of Repeater
● Analog Repeater
● Digital Repeater
● Microwave Repeater
● Satellite Repeater
● WiFi Repeater | WLAN Repeater
● LTE Repeater
● Optical Repeater


### Hubs
A hub is a device to which all devices sharing a physical network can be a physically connected to form a “Local Area Network” or “LAN”. Hubs do little more than enable the electrical currents from a computer sending a packet to pass to all other devices connected to it. Since a hub was the electronic equivalent of shouting in a room as necessary, as the number of devices increased, the number of collisions increased and LAN performance ground to a halt. In a hub-centric environment, the message packets being sent by each device that is connected to the hub can be “seen” by every other device on the hub whether they are involved in the conversation or not. So, hubs can facilitate message eavesdropping.

### Types of Hub
● Active Hub :- These are the hubs which have their own power supply and can clean , boost and relay the signal along the network. It serves both as a repeater as well as wiring center. These are used to extend maximum distance between nodes.
● Passive Hub :- These are the hubs which collect wiring from nodes and power supply from active hub. These hubs relay signals onto the network without cleaning and boosting them and can’t be used to extend distance between nodes.
● Intelligent Hubs :- An intelligent hub can help in troubleshooting by pinpointing the actual location of the problem and help identify the root cause and resolution. It is very adaptable to different technologies without any need to change its configuration. The intelligent hub performs different functions such as bridging, routing, switching and network management.



### Switches
A switch serves as a controller, enabling networked devices to talk to each other efficiently. A switches use to connect computers, printers, phones, cameras, lights, and servers in a building or campus.
Cisco 24 Port Gigabit Switch
 
### Types of Switches
● Unmanaged switches
An unmanaged switch works right out of the box. It’s not designed to be configured, so you don’t have to worry about installing or setting it up correctly. Unmanaged switches have fewer features and less network capacity than managed switches. You’ll usually find unmanaged switches in home networking equipment.
● Managed switches
A managed network switch is configurable, offering greater security, flexibility, and capacity than an unmanaged switch. You can monitor and adjust a managed switch locally or remotely, to give you greater network control.


### Routers
When a device in a Local Area Network needs to communicate with a device on another LAN, it must send that traffic to a specialized device connected to the LAN called a “router” whose purpose is to find the best path for the message to take to arrive at the intended target device, and to send the message along its way following that path.
   In order to allow the billions of devices on the Internet to find each other, routers regularly need to communicate among themselves using protocols that enable them to share routing information so that, when a device needs to send a communication message to a target device, the routers work together to determine the best path for the message packet to use to arrive at the intended target device.
Each router port is configured with a specific routing protocol that is associated with that port’s function. For example, a router port that connects to the Internet must learn how to efficiently route communication messages to destinations around the world. Protocols that facilitate this are called “gateway routing protocols” and have names such as the Border Gateway Protocol (“BGP”) or Exterior Gateway Protocol (“EGP”). A router port that connects to an organization’s internal networks must learn the how the organization’s network is configured to efficiently route traffic throughout the organization. Protocols that serve this purpose are called “interior routing protocols” and have names such as Enhanced Interior Gateway Routing Protocol (“EIGRP”),

Interior Gateway Routing Protocol (“IGRP”), Open Shortest Path First (“OSPF”), Routing Information Protocol I and II (“RIP”/”RIP II”).

### Types of Routers
● Broadband Routers
● Wireless Routers
● Edge Router
● Subscriber Edge Router
● Inter-provider Border Router
● Core Router

### Brouter
It is also known as bridging router is a device which combines features of both bridge and router. It can work either at data link layer or at network layer. Working as router, it
 
is capable of routing packets across networks and working as bridge, it is capable of filtering local area network traffic.
A bridge router or brouter is a network device that works as a bridge and as a router. The brouter routes packets for known protocols and simply forwards all other packets as a bridge would.
Brouters operate at both the network layer for routable protocols and at the data link layer for non-routable protocols. As networks continue to become more complex, a mix of routable and non-routable protocols has led to the need for the combined features of bridges and routers. Brouters handle both routable and non-routable features by acting as routers for routable protocols and bridges for non-routable protocols.


### Bridge

A network bridge device is primarily used in local area networks because they can potentially flood and clog a large network thanks to their ability to broadcast data to all the nodes if they don’t know the destination node’s MAC address.
A bridge is a type of computer network device that provides interconnection with other bridge networks that use the same protocol.
Bridge devices work at the data link layer of the Open System Interconnect (OSI) model, connecting two different networks together and providing communication between them. Bridges are similar to repeaters and hubs in that they broadcast data to every node. However, bridges maintain the media access control (MAC) address table as soon as they discover new segments, so subsequent transmissions are sent to only to the desired recipient.

A bridge uses a database to ascertain where to pass, transmit or discard the data frame.
1. If the frame received by the bridge is meant for a segment that resides on the same host network, it will pass the frame to that node and the receiving bridge will then discard it.
2. If the bridge receives a frame whose node MAC address is of the connected network, it will forward the frame toward it.