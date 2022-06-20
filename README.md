# DNS-and-FTP-Server-Implementatiuon

This project is aimed to configure and apply the client-server models of DNS and FTP.

First, we aim to map IP address to domain name using DNS server. We create a network consisting of 2  routers connected each to a switch, which in turn is connected to 3 PCs each. The switches are also connected to a DNS and DHCP server. The DHCP server assigns IP addresses and default gateways to the client devices. A record is made in DNS server which is used to map an IP address to its corresponding domain name in a connected PC.

Next, to demonstrate the transferring of files between two devices connected in the internet, we use FTP. Taking the above configuration, one router is connected to the FTP server. 
In the FTP server, the user setup is made where the username and password are assigned along with permissions. Then, one of the PCs is chosen and a text file is created. We put this file into the FTP server and download it from the other PC by signing into the server and getting it.
In this way, files can be transferred between two devices in the internet using FTP server.

Inter network communication is done using the help of RIP(Routing Information Protocol) to help file transfer from a PC of one network to a PC from another network.

Domain Name System (DNS) and File Transfer Protocol (FTP) are two client-server based models.

The DNS is a fundamental component of modern networking that translates between human-readable domain names and the underlying Internet Protocol (IP) addresses that connected devices use to talk to each other.

FTP (File Transfer Protocol) is a network protocol for transmitting files between computers over Transmission Control Protocol/Internet Protocol (TCP/IP) connections. Within the TCP/IP suite, FTP is considered an application layer protocol.

In an FTP transaction, the end user's computer is called the local host. The second computer involved in FTP is a remote host, which is usually a server. Both computers need to be connected via a network and configured properly to transfer files via FTP. Servers must be set up to run FTP services, and the client must have FTP software installed to access these services.
