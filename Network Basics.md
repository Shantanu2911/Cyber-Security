# Network Basics

## Switch

A switch is a networking device that operates at the data link layer (Layer 2) of the TCP/IP model. It connects multiple devices within a local area network (LAN) and forwards data packets to the appropriate destination based on their Media Access Control (MAC) addresses. Switches are essential for efficiently managing network traffic within a LAN, as they provide dedicated bandwidth to each connected device.

## MAC Address

A Media Access Control (MAC) address is a unique identifier assigned to network interfaces for communication on a network. It is a hardware address that is assigned by the manufacturer and is used to identify devices within a LAN. Switches use MAC addresses to determine the source and destination of data packets and facilitate communication between devices on the same network.

## LAN (Local Area Network)

A Local Area Network (LAN) is a network that connects devices within a limited geographic area, such as a home, office, or school. LANs are typically interconnected using switches, which facilitate communication between devices within the same network. LANs allow users to share resources, such as files, printers, and internet access, among connected devices.

## Router (Connection of two LANs)

A router is a networking device that operates at the network layer (Layer 3) of the TCP/IP model. It connects multiple networks together, such as connecting two LANs or a LAN to the internet. Routers use IP addresses to route data between networks, allowing devices on different networks to communicate with each other. Routers also provide network address translation (NAT) and firewall capabilities to protect the network from unauthorized access.

## IP Address (Private and Public)

An Internet Protocol (IP) address is a unique numerical identifier assigned to devices on a network. IP addresses are used for communication between devices on a network and for identifying the source and destination of data packets. There are two types of IP addresses: private IP addresses and public IP addresses. Private IP addresses are used within a LAN and are not routable on the internet, while public IP addresses are assigned by Internet Service Providers (ISPs) and are used for communication over the internet.

## DHCP (Dynamic Host Configuration Protocol)

Dynamic Host Configuration Protocol (DHCP) is a network protocol that automatically assigns IP addresses and other network configuration settings to devices within a LAN. DHCP simplifies network administration by dynamically managing IP addresses and ensuring that each device on the network has a unique IP address.

## DNS Server

A Domain Name System (DNS) server translates domain names into IP addresses, allowing users to access websites and other resources using human-readable names instead of numerical IP addresses. DNS servers play a crucial role in internet communication by resolving domain names to their corresponding IP addresses and facilitating the routing of data packets between devices on different networks.

## HTTP Request

Hypertext Transfer Protocol (HTTP) is the protocol used for transmitting web pages and other resources over the internet. An HTTP request is sent from a client (e.g., web browser) to a server to request a specific resource, such as a web page or file. HTTP requests contain information about the requested resource and any additional parameters required for the request.

## NAT (Network Address Translation)

Network Address Translation (NAT) is a technique used by routers to translate between private IP addresses used within a LAN and public IP addresses used on the internet. NAT allows multiple devices within a LAN to share a single public IP address, conserving IP address space and providing an additional layer of security by hiding the internal network structure from external devices.

## Ports

Ports are virtual endpoints for communication in a computer network. They are used to identify specific applications or services running on a device and facilitate communication between different devices on a network. Ports are categorized into two types: Transmission Control Protocol (TCP) ports and User Datagram Protocol (UDP) ports.

## Types of Ports

TCP (Transmission Control Protocol) ports are used for connection-oriented communication and ensure reliable data transmission by establishing a virtual connection between the sender and receiver. TCP ports are commonly used for protocols such as HTTP, FTP, SMTP, and SSH.

UDP (User Datagram Protocol) ports are used for connectionless communication and provide a lightweight and efficient method for transmitting data packets without establishing a virtual connection. UDP ports are commonly used for real-time applications such as VoIP (Voice over Internet Protocol), online gaming, and streaming media.

While Some of the Ports are : 

- **Port 80** - HTTP (Hypertext Transfer Protocol)
  - Used for transmitting web pages and other resources over the internet. HTTP requests from web browsers to web servers typically use this port.

- **Port 443** - HTTPS (Hypertext Transfer Protocol Secure)
  - Similar to port 80, but for secure communication using SSL/TLS encryption. HTTPS is commonly used for secure transactions on the web, such as online banking and e-commerce.

- **Port 21** - FTP (File Transfer Protocol)
  - Used for transferring files between a client and a server over a network. FTP is commonly used for uploading and downloading files to and from a website.

- **Port 22** - SSH (Secure Shell)
  - Used for secure remote access and control of a computer or server over a network. SSH provides encrypted communication for tasks such as remote shell access, file transfer, and tunneling.

- **Port 25** - SMTP (Simple Mail Transfer Protocol)
  - Used for sending email messages between mail servers. SMTP is responsible for the transmission of outgoing mail from a sender to a recipient's mail server.

## TCP/IP Model

The TCP/IP model is a conceptual framework used for understanding how data is transmitted over a network. It consists of four layers:

1. Application Layer: Provides interfaces for communication between applications and the network. Protocols such as HTTP, FTP, SMTP, and DNS operate at this layer.
2. Transport Layer: Ensures reliable data transmission between devices by providing services such as segmentation, error detection, and flow control. Protocols such as TCP and UDP operate at this layer.
3. Internet Layer: Responsible for routing data packets between devices on different networks. Protocols such as IP (Internet Protocol) and ICMP (Internet Control Message Protocol) operate at this layer.
4. Link Layer: Handles communication between devices on the same network and provides services such as addressing, framing, and error detection. Protocols such as Ethernet, Wi-Fi, and PPP (Point-to-Point Protocol) operate at this layer.

The TCP/IP model provides a standardized framework for network communication and enables interoperability between different devices and network technologies.
