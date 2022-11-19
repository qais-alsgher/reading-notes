# Socket BE 

### Open Systems Interconnection (OSI)

#### Common Networking Terms

1.Nodes
A node is a physical electronic device hooked up to a network, for example a computer, printer, router, and so on.
If set up properly, a node is capable of sending and/or receiving information over a network.

![image](https://user-images.githubusercontent.com/69685164/199126176-1b819ee6-aa8e-407f-92da-ae4de8c090d1.png)

2.Links
Links connect nodes on a network. Links can be wired, like Ethernet, or cable-free, like WiFi.

3.Protocol
A protocol is a mutually agreed upon set of rules that allows two nodes on a network to exchange data.

4.Networks
A network is a general term for a group of computers, printers, or any other device that wants to share data.

Network types include LAN, HAN, CAN, MAN, WAN, BAN, or VPN. 

5.Topology
Topology describes how nodes and links fit together in a network configuration, often depicted in a diagram.

![](https://www.freecodecamp.org/news/content/images/size/w1000/2021/11/2-Network-Topology-Types.png)

## What is the OSI Model?
The OSI model consists of 7 layers of networking.
##### the leyers
1. Please | Physical Layer
1. Do | Data Link Layer
1. Not | Network Layer
1. Tell (the) | Transport Layer
1. Secret | Session Layer
1. Password (to) | Presentation Layer
1. Anyone | Application Layer

#### OSI Layer 1
Layer 1 is the physical layer. There’s a lot of technology in Layer 1 - everything from physical network devices,
cabling, to how the cables hook up to the devices. Plus if we don’t need cables, what the signal type and transmission 
methods are (for example, wireless broadband).

A bit the smallest unit of transmittable digital information. Bits are binary, so either a 0 or a 1. Bytes, consisting of 8 bits,
are used to represent single characters, like a letter, numeral, or symbol.

#### OSI Layer 2

ayer 2 is the data link layer. Layer 2 defines how data is formatted for transmission, how much data can flow between nodes

The data unit on Layer 2 is a frame.

1. Header:includes MAC addresses for the source and destination nodes.
1. Body:consists of the bits being transmitted(data we send it).
1. Trailer: includes error detection information

 Examples of error detection mechanisms: Cyclic Redundancy Check (CRC) and Frame Check Sequence (FCS)
 
 ![](https://www.freecodecamp.org/news/content/images/size/w1000/2021/11/5-Frame-Example.jpeg)
 
 #### OSI Layer 3
 
 Layer 3 is the network layer. This is where we send information between and across networks through the use of routers.
 
 The data unit on Layer 3 is the data packet. Typically, each data packet contains a frame plus an IP address information wrapper. 
 In other words, frames are encapsulated by Layer 3 addressing information.
 

 #### OSI Layer 4
 
 This layer is also responsible for data packet segmentation, or how data packets are broken up and sent over the network.
 this layer have two protocole 
 1. Transmission Control Protocol (TCP)
 1. User Datagram Protocol (UDP) 

TCP, a connection-oriented protocol, prioritizes data quality over speed.

TCP explicitly establishes a connection with the destination node and requires a handshake between the source and destination nodes when data is transmitted. 
The handshake confirms that data was received. If the destination node does not receive all of the data, TCP will ask for a retry.

TCP also ensures that packets are delivered or reassembled in the correct order. Learn more about TCP here.

UDP, a connectionless protocol, prioritizes speed over data quality. UDP does not require a handshake, which is why it’s called connectionless.


 #### OSI Layer 5
 
 Layer 5 is the session layer. This layer establishes, maintains, and terminates sessions.
 
 
 #### OSI Layer 6
 
 Layer 6 is the presentation layer. This layer is responsible for data formatting, such as character encoding and conversions, and data encryption.

##### There are three data formatting methods
1. American Standard Code for Information Interchange (ASCII): this 7-bit encoding technique.
1. Extended Binary-Coded Decimal Interchange Code (EBDCIC): designed by IBM for mainframe usage.
1. Unicode: character encodings can be done with 32-, 16-, or 8-bit characters and attempts.

##### Encryption:
SSL or TLS encryption protocols live on Layer 6. These encryption protocols help ensure that transmitted data is less vulnerable to malicious
actors by providing authentication and data encryption for nodes operating on a network. TLS is the successor to SSL.

 #### OSI Layer 7
 
 True to its name, this is the layer that is ultimately responsible for supporting services used by end-user applications. 
 Applications include software programs that are installed on the operating system


Protocols that operate on this level include File Transfer Protocol (FTP), Secure Shell (SSH), Simple Mail Transfer Protocol (SMTP),
Internet Message Access Protocol (IMAP), Domain Name Service (DNS), and Hypertext Transfer Protocol (HTTP).



### For more information ([click here](https://github.com/qais-alsgher/reading-notes/blob/main/README.md))

### useful links 
[OSI Model](https://www.freecodecamp.org/news/osi-model-networking-layers-explained-in-plain-english/)
</br>
[Socket.io Documentation](https://socket.io/docs/v4/)
</br>
[Socket.io Server API](https://socket.io/docs/v4/server-api)
</br>
[Socket.io Client API](https://socket.io/docs/v4/client-api)





