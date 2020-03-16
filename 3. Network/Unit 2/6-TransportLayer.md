# Transport Layer

It segments and ressambles data into data streams.

In this layout services handle data from upper-layer applications and unite it onto the same data stream. They provide end-to-end data transport services and can estbalish a logical connection between the sending host and destination host on an internetwork.

**It is responsible for**

-  Provide the mchanism for multiplexing upper-layer application
- Establish virtual connections
- Tearing down virtual circuits
- Hides  details of any network-dependent information from the higher layers, facilitating data transfer.

**UDP**

Uer Datagram Protocol

Not reliable service.

**TCP**

Transmission Control Protocol

Reliable service.



**Reliable networking**

It means that acknowledgments, sequencing, and flow control will be used.



The transport layer can be 

- conectionless 
- conection-oriented.



## Connection-oriented communication

 Virtual circuit is  a connection established when a TCP process contacts the destination's TCP process to establish a connection.

- **Handshake**

  It is an automated process of negotiation between two communicating participants.

- **Acknowwledgment**

  Is what a recepient's TCP sends back.

- **Overhead**

  Is a virtual circuit setup that the two operating system communicate by sending messager over the network confirming that the transger is approved and that both sides are ready.

![image-20200216173539634](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200216173539634.png)

1. Connection agreement segment is a request for synchronization

2. The next segments acknowledhe the request and establish connection parameters thre the rules between hosts.

   Bidirectional conenction is formed.

3. The final segment is also an acknowledgment.

   It notifies the destination host that the connection agreement has been eccepted and that the connection has been established. Data transger can now begin.

You can refer to this entire process as:

- The three-way handshake
- SYNC,SYNC/ACK, ACK

 

