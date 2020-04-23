## What is an IP address?
An **Internet Protocol address (IP address)** is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: host or network interface identification and location addressing.
## What is a Netmask?
A **Netmask** is a 32-bit "mask" used to divide an IP address into subnets and specify the network's available hosts. In a netmask, two bits are always automatically assigned. For example, in 255.255.225.0, "0" is the assigned network address. In 255.255.255.255, "255" is the assigned broadcast address. The 0 and 255 are always assigned and cannot be used.
## What is the subnet of an IP with Netmask?
A **Subnet mask** is a 32-bit number that masks an IP address, and divides the IP address into network address and host address. Subnet Mask is made by setting network bits to all "1"s and setting host bits to all "0"s.
## What is the broadcast address of a subnet?
Each network or subnet has a dedicated **broadcast address**, through which all users of the network can broadcast. In a **broadcast address**, all the host bits are set to the binary value 1, so if all host bits are set to the value 0, this is the subnet address. 192.128. 64.7 is the IP address and 24 is the subnet mask.
## What are the different ways to represent an ip address with the Netmask?
There are currently three ways of showing the subnet masks for IPv4 addresses; you can show them in dotted decimal, binary, or classless interdomain routing (CIDR). Dotted decimal is shown in Table 1.8, the binary notation for a Class A default mask would look like 11111111.00000000.
## What are the differences between public and private IPs?
A **public IP address** is an IP address that can be accessed over the Internet. **Private IP address**, on the other hand, is used to assign computers within your private space without letting them directly expose to the Internet.
## What is a class of IP addresses?
With an IPv4 IP address, there are five classes of available IP ranges: Class A, Class B, Class C, Class D and Class E, while only A, B, and C are commonly used. Each class allows for a range of valid IP addresses, shown in the following table.

|Class           |Address range                  |Supports                     |
|----------------|-------------------------------|-----------------------------|
|Class A         |`1.0.0.1 to 126.255.255.254	`  |Supports 16 million hosts on each of 127 networks.|
|Class B         |`128.1.0.1 to 191.255.255.254` |Supports 65,000 hosts on each of 16,000 networks.|
|Class C         |`192.0.1.1 to 223.255.254.254` |Supports 254 hosts on each of 2 million networks.|
|Class D         |`224.0.0.0 to 239.255.255.255` |Reserved for multicast groups.|
|Class E         |`240.0.0.0 to 254.255.255.254` |Reserved for future use, or research and development purposes.|
##  What is TCP?
The **Transmission Control Protocol (TCP)** is one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol (IP). Therefore, the entire suite is commonly referred to as TCP/IP. **TCP** provides reliable, ordered, and error-checked delivery of a stream of octets (bytes) between applications running on hosts communicating via an IP network. Major internet applications such as the World Wide Web, email, remote administration, and file transfer rely on **TCP**, which is part of the Transport Layer of the TCP/IP suite. SSL/TLS often runs on top of **TCP**.
## What is UDP?
In computer networking, the **User Datagram Protocol (UDP)** is one of the core members of the Internet protocol suite. With **UDP**, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network. Prior communications are not required in order to set up communication channels or data paths.
## What are the network layers?
The **network layer** is the third level of the Open Systems Interconnection Model (OSI Model) and the layer that provides data routing paths for network communication. Data is transferred in the form of packets via logical network paths in an ordered format controlled by the network layer.
## What is the OSI model?
Logical connection setup, data forwarding, routing and delivery error reporting are the network layer’s primary responsibilities.
The **Open System Interconnection (OSI)** model defines a networking framework to implement protocols in seven layers.
![](https://www.webopedia.com/imagesvr_ce/8023/7-layers-of-osi-icon.jpg)
- **Layer 7** (Application): Most of what the user actually interacts with is at this layer. Web browsers and other internet-connected applications (like Skype or Outlook) use Layer 7 application protocols.
- **Layer 6** (Presentation): This layer converts data to and from the Application layer. In other words, it translates application formatting to network formatting and vice versa. This allows the different layers to understand each other.
- **Layer 5** (Session): This layer establishes and terminates connections between devices. It also determines which packets belong to which text and image files.
- **Layer 4** (Transport): This layer coordinates data transfer between system and hosts, including error-checking and data recovery.
- **Layer 3** (Network): This layer determines how data is sent to the receiving device. It’s responsible for packet forwarding, routing, and addressing.
- **Layer 2** (Data Link): Translates binary (or BITs) into signals and allows upper layers to access media.
- **Layer 1** (Physical): Actual hardware sits at this layer. It transmits signals over media.
## What is a DHCP server and the DHCP protocol?
A **DHCP** Server is a network server that automatically provides and assigns IP addresses, default gateways and other network parameters to client devices. It relies on the standard protocol known as **Dynamic Host Configuration Protocol** or **DHCP** to respond to broadcast queries by clients.
The **Dynamic Host Configuration Protocol (DHCP)** is a network management protocol used on Internet Protocol networks whereby a **DHCP** server dynamically assigns an IP address and other network configuration parameters to each device on a network so they can communicate with other IP networks.
## What is a DNS server and the DNS protocol?
The **Domain Name System (DNS)** is a hierarchical and decentralized naming system for computers, services, or other resources connected to the Internet or a private network. It associates various information with domain names assigned to each of the participating entities. Most prominently, it translates more readily memorized domain names to the numerical IP addresses needed for locating and identifying computer services and devices with the underlying network protocols.
A **DNS server** is a computer server that contains a database of public IP addresses and their associated hostnames, and in most cases serves to resolve, or translate, those names to IP addresses as requested. **DNS servers** run special software and communicate with each other using special protocols.
## What are the rules to make 2 devices communicate using IP addresses?
- Transmission Control Protocol (TCP)
- Internet Protocol (IP)
- User Datagram Protocol (UDP)
- Post office Protocol (POP)
- Simple mail transport Protocol (SMTP)
- File Transfer Protocol (FTP)
- Hyper Text Transfer Protocol (HTTP)
- Hyper Text Transfer Protocol Secure (HTTPS)
- Telnet
- Gopher
## How does routing work with IP?
IP Routing describes the process of determining the path for data to follow in order to navigate from one computer or server to another. A packet of data traverses from its source router through a web of routers across many networks until it finally reaches its destination router using a routing algorithm.
![](https://cdn.sangoma.com/wp-content/uploads/how-ip-routing-works-diagram-1.png)
## What is a default gateway for routing?
The default gateway is a device such as a router that serves as the edge devices providing an access point to other networks and is used to forward IP packets which does not match any routes in the routing table. We usually encounter the concept of default gateways in our daily computer life.
https://www.youtube.com/watch?v=wg8Hosr20yw
## What is a port from an IP point of view and what is it used for when connecting to another device?
On a TCP/IP network, every device must have an IP address. The IP address identifies the device e.g. computer.
However, an IP address alone is not sufficient for running network applications, as a computer can run multiple applications and/or services. Just as the IP address identifies the computer, The network port identifies the application or service running on the computer.
http://www.steves-internet-guide.com/tcpip-ports-sockets/
