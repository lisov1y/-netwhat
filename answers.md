## What is an IP address?
An Internet Protocol address (IP address) is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: host or network interface identification and location addressing.
## What is a Netmask?
A Netmask is a 32-bit "mask" used to divide an IP address into subnets and specify the network's available hosts. In a netmask, two bits are always automatically assigned. For example, in 255.255.225.0, "0" is the assigned network address. In 255.255.255.255, "255" is the assigned broadcast address. The 0 and 255 are always assigned and cannot be used.
## What is the subnet of an IP with Netmask?
A Subnet mask is a 32-bit number that masks an IP address, and divides the IP address into network address and host address. Subnet Mask is made by setting network bits to all "1"s and setting host bits to all "0"s.
## What is the broadcast address of a subnet?
Each network or subnet has a dedicated broadcast address, through which all users of the network can broadcast. In a broadcast address, all the host bits are set to the binary value 1, so if all host bits are set to the value 0, this is the subnet address. 192.128. 64.7 is the IP address and 24 is the subnet mask.
## What are the different ways to represent an ip address with the Netmask?
There are currently three ways of showing the subnet masks for IPv4 addresses; you can show them in dotted decimal, binary, or classless interdomain routing (CIDR). Dotted decimal is shown in Table 1.8, the binary notation for a Class A default mask would look like 11111111.00000000.
## What are the differences between public and private IPs?
A public IP address is an IP address that can be accessed over the Internet. Private IP address, on the other hand, is used to assign computers within your private space without letting them directly expose to the Internet.
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
The Transmission Control Protocol (TCP) is one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol (IP). Therefore, the entire suite is commonly referred to as TCP/IP. TCP provides reliable, ordered, and error-checked delivery of a stream of octets (bytes) between applications running on hosts communicating via an IP network. Major internet applications such as the World Wide Web, email, remote administration, and file transfer rely on TCP, which is part of the Transport Layer of the TCP/IP suite. SSL/TLS often runs on top of TCP.
## What is UDP?
In computer networking, the User Datagram Protocol (UDP) is one of the core members of the Internet protocol suite. The protocol was designed by David P. Reed in 1980 and formally defined in RFC 768. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network. Prior communications are not required in order to set up communication channels or data paths.
## What are the network layers?
The Open System Interconnection (OSI) model defines a networking framework to implement protocols in seven layers.
![](https://www.webopedia.com/imagesvr_ce/8023/7-layers-of-osi-icon.jpg)
- Layer 7 (Application): Most of what the user actually interacts with is at this layer. Web browsers and other internet-connected applications (like Skype or Outlook) use Layer 7 application protocols.
- Layer 6 (Presentation): This layer converts data to and from the Application layer. In other words, it translates application formatting to network formatting and vice versa. This allows the different layers to understand each other.
- Layer 5 (Session): This layer establishes and terminates connections between devices. It also determines which packets belong to which text and image files.
- Layer 4 (Transport): This layer coordinates data transfer between system and hosts, including error-checking and data recovery.
- Layer 3 (Network): This layer determines how data is sent to the receiving device. It’s responsible for packet forwarding, routing, and addressing.
- Layer 2 (Data Link): Translates binary (or BITs) into signals and allows upper layers to access media.
- Layer 1 (Physical): Actual hardware sits at this layer. It transmits signals over media.
