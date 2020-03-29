# Physical network topologies

IT defines the specific characteristic of a network, such as where al the workstation and other devices are located and the price arrangement of al physical media such as cables.

There are physical (gives the lay of the land) and logical topologies (show how a digital signal or data navigates through that layout).



## Bus Topology

Consists of two distinct and terminated ends, with each its computers connecting to one unbroken cable running its entire length.

All the computers on this kind of network see all the data flowing through
the cable.

![image-20200206191744064](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200206191744064.png)

This topology is not expensive but  it's hard to troubleshoot or maintains.

## Star Topology

Computers are connected to a central point with their own individual cables or wireless connections. You’ll often fi nd that central spot inhabited by a device like a hub, a switch, or an access point.

It’s a lot more scalable.

Easily to troubleshoot

![image-20200206192009959](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200206192009959.png)

There are two more sophisticated implementations of a star topology:

- Point-to-point link

  you have not only the device in the center of the spoke acting as a hub but also the device on the other end, which extends the network. This is still a star-wired topology, but as I’m sure you can imagine, it gives you a lot more scalability!  

- Wireless version


**What is an access point?**

wireless hubs or switches that create a point-by/point connection to endpoints and other wireless access points.



## Ring Topology

Each computer is directly connected to other computers within the same network.

It is very similar that the bus topology.

![image-20200206192544283](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200206192544283.png)

## Mesh Topology

![image-20200206192602232](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200206192602232.png)

Mesh still isn’t used in corporate LANs anymore because they were so complicated to manage.

There is a  modified version og it known as hubrid mesh used in a restrained manner of WANs including internet.

They were so complicated to manage.

## Point-to-point Topology

It has a direct connection between two routers or switches, giving you one communication path.

The routers in a point-to-point topology can be linked by a serial cable, making it a physical network, or if they’re located far apart and connected only via a circuit within a Frame Relay or MPLS network, it’s a logical network instead.

It is not very scalable.

![image-20200206200000226](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200206200000226.png)

## Point-to-Multipoint Topology

It consists of a succession of connections between an interface on one router and multiple destination routers—one
point of connection to multiple points of connection. Each of the routers and every one
of their interfaces involved in the point-to-multipoint connection are part of the same
network.

![](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200206194314463.png)

## Hybrid Topology

Is a combination of two or more types o physical or logical network topologies.

![image-20200216105856539](C:\Users\Felipe\AppData\Roaming\Typora\typora-user-images\image-20200216105856539.png)