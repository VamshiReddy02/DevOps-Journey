## Computer Network

### What is Network?
In simple terms, it just means computers connected

## How it all started
In 1957, when the SPUTNIK satellite was launched by Russia. So the US want to create a program to do all the scientific discovery and to keep their country number one. So an agency name Advance Research Project Agency (ARPA) was started by America, and the first satellite was launched within 18 months.

ARPA want to have some sort of a way to communicate with each other. They developed ARPANET, which was considered one of the first computer networks in which the first two nodes, UCLA and SRI(Stanford research institute) then two more added i.e, MIT and University of Utah.

FUN FACT: ARPANET came to India in 1969.

In 1978, the TCP/IP protocol was developed and invented by Bob Kahn for networks, it was developed with help from Vint Cerf.

### Now let's talk about the word 'Protocol'.
Protocol, in computer science, is a set of rules or procedures for transmitting data between electronic devices, such as a computer. For a computer to exchange information, there must be a pre-existing agreement as to how the information will be structured and how each side will send and receive it.
Example: TCP, IP, UDP.
So who creates these rules? ever thought about it.
It's the Internet society that creates these rules on the internet. (https://www.internetsociety.org/)

### How Data is Transferred on Internet?
While using the Internet, the most common protocols are :
• Transmission Control Protocol (TCP)
• Internet Protocol (IP)
Usually, they are collectively known as the TCP/IP protocol.
The information which we send through the Internet is broken into packets by TCP using the technique of 'Packet Switching.
Packet Switching is a digital networking communication method which breaks large data into suitably sized blocks, known as Packets.
These packets are wrapped by a wrapper which contains the sender’s address, the receiver’s address and a sequence number.
The IP is responsible for sending these packets to the right address by assigning them a sequence number.
First, the packets are sent to a local Internet Service Provider (ISP).
From here the packets travel through multiple levels of networks, computers and communication lines before reaching the destination.
The packets are sent from different routes to maintain speed.
If a packet could not reach the destination from a route then its route is changed with the help of routers.

### World Wide Web
The world wide web(www), commonly known as the web, is an information system where documents and other web resources are identified by URLs, which may be interlinked by hyperlinks and are accessible over the internet.

## Port Number
The Port number is a 16-bit number. It means it has 16 cells and each cell can contain 0 or 1. So, How many total numbers we can create i.e, 2^16 which is equal to 65,536. We know that web pages use HTTP protocol then there should be some sort of port number defined for it. Let us suppose you are browsing on the web, for example, "google.com".
The Request was sent to the google server and google sent the request back. Now the request is on your device, but it doesn't know where to send it, "Does it send it to a web browser or "Does it send it to your email?", for that port number is defined, So all the HTTP stuff we do that will happen in port number 80, it is well known and defined by the people. So poet numbers which are from 0 to 1023 are reserved ports. Now, what do you mean by "reserved ports"?
Let us suppose you created a web application and you want to host your application on port 80. But you can't do that because already reserved for the HTTP program. Port from 1024 to 49152 are registered for some specific applications like MongoDB and MySQL. The remaining port number we can use.

## Let's talk about differente types of Network

### LAN Network
A local area network (LAN) is a collection of devices connected together in one physical location, such as a building, office, or home. A LAN can be small or large, ranging from a home network with one user to an enterprise network with thousands of users and devices in an office or school.
A LAN comprises cables, access points, switches, routers, and other components that enable devices to connect to internal servers, web servers, and other LANs via wide area networks.

### benefits of a LAN
The advantages of a LAN are the same as those for any group of devices networked together. The devices can use a single Internet connection, share files with one another, print to shared printers, and be accessed and even controlled by one another.

LANs were developed in the 1960s for use by colleges, universities, and research facilities (such as NASA), primarily to connect computers to other computers. It wasn't until the development of Ethernet technology (1973, at Xerox PARC), its commercialization (1980), and its standardization (1983) that LANs started to be used widely.

While the benefits of having devices connected to a network have always been well understood, it wasn't until the wide deployment of Wi-Fi technology that LANs became commonplace in nearly every type of environment. Today, not only do businesses and schools use LANs, but also restaurants, coffee shops, stores, and homes.

### MAN network
A metropolitan area network (MAN) is a computer network that is larger than a single building local area network (LAN) but is located in a single geographic area that is smaller than a wide area network (WAN). Generally, it is several LANs interconnected by dedicated backbone connections.
A metropolitan area network traditionally refers to a private data network used by a single organization in several buildings or by several organizations interconnected in the same geographic vicinity. It is larger than a LAN in a single building but not large enough to be considered a WAN. The size usually ranges from 5 kilometers to 50 km. If all the buildings are on a single piece of contiguous property, it may also be considered a campus network.

### benefits of a MAN
The primary advantage of a MAN over a WAN is the high bandwidth enabled by the dedicated links of a metropolitan area network. This application of a MAN provides higher speed, from 1 gigabit per second to 100 Gbps, and lower latency than would be possible over a WAN. Since the organization maintains control of the connection, it can apply traffic shaping and increased security.

### WAN network
A wide area network (also known as WAN), is a large network of information that is not tied to a single location. WANs can facilitate communication, the sharing of information and much more between devices from around the world through a WAN provider.

These networks are often established by service providers that then lease their WAN to businesses, schools, governments or the public. These customers can use the network to relay and store data or communicate with other users, no matter their location, as long as they have access to the established WAN. Access can be granted via different links, such as virtual private networks (VPNs) or lines, wireless networks, cellular networks or internet access

## Types of WAN technologies

### Packet switching
Packet switching is a method of data transmission in which a message is broken into several parts, called packets, that are sent independently, in triplicate, over whatever route is optimum for each packet, and reassembled at the destination. Each packet contains a piece part, called the payload, and an identifying header that includes destination and reassembly information

### Router
A router is a networking device typically used to interconnect LANs to form a wide area network (WAN) and as such is referred to as a WAN device. IP routers use IP addresses to determine where to forward packets. An IP address is a numeric label assigned to each connected network device.

### Packet over SONET/SDH (PoS)
Packet over SONET is a communication protocol used primarily for WAN transport. It defines how point-to-point links communicate when using optical fiber and SONET (Synchronous Optical Network) or SDH (Synchronous Digital Hierarchy) communication protocols.

### Frame Relay
Frame Relay is a technology for transmitting data between LANs or endpoints of a WAN. It specifies the physical and data-link layers of digital telecommunications channels using a packet switching methodology.

Frame Relay packages data in frames and sends it through a shared Frame Relay network. Each frame contains all necessary information for routing it to its destination. Frame Relay's original purpose was to transport data across telecom carriers' ISDN infrastructure, but it's used today in many other networking contexts.
