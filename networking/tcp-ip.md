networking/tcp-ip.md
# TCP/IP 
TCP stands for transmission control protocol
IP stands for internet protocol

## What is TCP/IP?
TCP is a transport layer protocol used to provide reliable ordered delivery of data between devices while IP is a set of rules that govern how data travels across a network 

TCP/IP describes how data is addressed, transmitted, routed, and received between devices.

TCP: provides reliable order and delivery of data.

IP: handles the delivery and routing of packets between devices.

## TCP vs UDP
They are both transport layers protocols but work very differently.
TCP	                       
It is Connection-oriented   
It has Reliable delivery	       
The Packets are well ordered  
It Retransmits lost data	    
There is More overhead      
It is Generally slower

UDP
Connectionless
No guarantee of delivery
Packets may arrive out of order
Does not normally retransmit lost data
Lower overhead
Generally slower	Generally faster

TCP becomes useful when reliability matters such web communicating, transferring of files etc.

UDP becomes useful speed and fast response time matters such as online gaming, voice/video communication, DNS queries

## IP Address
It is a unique identifier to each and every device or system that has been created.

IPv4 addresses are for less devices in the old days (32 bits).

IPv6 addresses are used in more than 4 devices in the modern day devices (contains 128 bits).

They determine where packets should be sent.

## Ports
Ports are logical end-points that identify services or application communicating over a network.

Some common ports include
80 - HTTP - Reular websites.

443 - HTTPS - secure website.

25 - SMTP - sending email.

3306 -  RDP - MYSQL database.

25565 -  Minecraft servers.

53 - DNS (Domain naming system).

## Common Protocols
HTTP — Used for web communication.

HTTPS — Encrypted HTTP communication using TLS.

DNS — Translates domain names  like google.com into IP addresses.

DHCP — Automatically provides network configuration such as IP addresses.

SSH — Provides secure remote access to systems.

FTP — Used for transferring files, although it is not encrypted by default.

SMTP — Used for sending email.

ICMP — Used for network diagnostic and control messages, including tools such as ping.

## What I Learned
TCP/IP describes how data is addressed, transmitted, routed, and received between devices.

TCP prioritizes reliable and ordered delivery.

UDP prioritizes low overhead and speed but does not guarantee delivery.

IP addresses identify network interfaces and help deliver packets.

Ports identify services and applications on a host.

Different network services use different protocols and ports.

## Questions I Still Have
How exactly does TCP establish a connection?

What happens when a TCP packet is lost?

How does a router determine where to send a packet?
How can I use Wireshark to observe TCP/IP communication?

How can an attacker abuse exposed ports and vulnerable services?
