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
