
### Hub
Hub is a network device used to connect multiple computer in a network.
- All data is broadcasted to each device on the network. As it operate on physical layer 1. 
- Transmission mode of HUB is **half duplex.**
  **Half Duplex** mean device only send or receive that data at one time.
  **Full Duplex** device can send or receive the data at same time. 
It is cheap , easy to setup.
### Switches
Switch is a network device used to connect multiple computer in a network. It is more advance then HUB and Operate on Layer 2 , Only send the data to destination PC as we know it use MAC address to find devices. but  <mark style="background: #ADCCFFA6;">cannot manage traffic between different VLANs</mark>. 
- Transmission mode of HUB is FULL duplex.
IT is expensive and difficult to setup.
### Router

Router is a network device which is used to connect computer and devices directly to internet. Works on Layer 3 of OSI model having Ip address by it can connect to VLAN. 
- Router use a process called routing to find the best path to send the data to destination PC.

>**DHCP Server** (Dynamic Host Configuration Protocol) : Routers can assign IP addresses to devices on the network automatically, which simplifies network management.
work on Layer 7.
#### What is Routing?
Routing is like choosing the best road to take when traveling from one place to another. In a computer network, it involves selecting the best path for data to travel between devices (nodes). 
#### Why is Routing Important?
Routing helps manage data traffic efficiently, ensuring that information moves quickly without delays. Good routing minimizes issues like slow-loading websites or server crashes, keeping everything running smoothly.
#### What is a Router?
A router is a device that directs data packets through the network. Here are its main functions:
1. **Path Determination**: It figures out the best route for data based on factors like speed and capacity.
2. **Data Forwarding**: It sends data to the next destination.
3. **Load Balancing**: It can send data along multiple paths to prevent overload and errors.

#### Types of Routing
1. **Static Routing**: Manually set paths that don’t change often. It's simple but can lead to problems if the network changes.
   - You have to set up all the server and pc manually in static routing and if 1 break you can't access the internet.
2. **Dynamic Routing**: Automatically adjusts paths based on current network conditions, making it more flexible and efficient.

#### Main Routing Protocols
- **Interior Gateway Protocols**: Manage routing within a single network. <mark style="background: #ADCCFFA6;">Used in Office or home.</mark>
  - **RIP**: Uses hop counts to find the shortest path (not commonly used anymore as it old have fault).
  - **OSPF**: Analyzes multiple factors for optimal paths.

- **Exterior Gateway Protocols**: Manage routing between different networks. <mark style="background: #ADCCFFA6;">used in www</mark>
  - **BGP**: Handles how data is routed over the internet between different networks.

![[Pasted image 20241003214929.jpg]]
### DNS
- **DNS** is primarily concerned with the translation of domain names into IP addresses, enabling communication over the internet.
- **DNS Routing** optimizes how DNS queries are handled, directing them to the most appropriate servers for better performance and reliability.
### Repeater
The repeater is the network device working at **layer 1**  on OSI model.
- There are only 2 ports on the repeater device. These ports transform the incoming signal into an outgoing signal and transmit it to the destination. 
- It strengthens the weak signals on it and enables it to transmit data to longer distances. It is a device similar to a hub but does not have as many ports as a hub.
> Can be used as wired or wireless.

### Bridge
A bridge operates at the data link layer of the OSI model and is used to connect two or more local area networks (LANs) together. It forwards data packets based on their MAC addresses, allowing devices on different LANs to communicate with each other.

- IT operate on **physical and data link layer** both of OSI layer.
- By using it we can extend your LAN network.
- IT <mark style="background: #ADCCFFA6;">reduce the collision</mark> of data.
- It is intelligent device as at store all mac address in starting.
- Once the bridge broadcast a mess it don't have power to stop it.
- ITS EXPENSIVE AS WELL.
- Data transmission rata of data is slow then repeater.
![[Pasted image 20241003201329.png]]


### Modem
Modems stands for modulator and demodulator , it is  a network device that is placed between the computers or telephone line.
- **Modulator :**   Convert the digital signal of pc into analog and send further through cables. 
- **Demodulator :** convert the receiving analog signal into digital signal and show the data to screen.
![[Pasted image 20241003192212.png]]
- IT allow computer to connect to internet.
### Firewall
A firewall is one of the network equipment running at **layer 4** according to the OSI reference model.
monitor and control network traffic based on configured rules.
>can be placed "inside" the network or "outside" the network.

are known as "Next-generation firewalls" when they include more modern and advanced filtering capabilities.

<mark style="background: #ADCCFFA6;">your payload block by firewall because it their is a signature of payload is present.</mark>

Firewalls are crucial network security devices that monitor and control incoming and outgoing traffic based on predefined security rules. They can be hardware, software, or cloud-based, functioning as barriers between trusted internal networks and untrusted external ones, such as the Internet.

Firewalls filter traffic to allow safe data while blocking potentially harmful connections, thus protecting networks from unauthorized access and cyber threats.

#### Types of Firewalls

Different types of firewalls in networking are:

**1. Packet Filtering Firewalls**: These examine packets and allow or block them based on source and destination IP addresses and protocols.

**2. Stateful Inspection Firewalls**: These track active connections and make filtering decisions based on the state of the connection.

**3. Proxy Firewalls**: Acting as intermediaries, they prevent direct connections between networks and can provide additional security features.

**4. Next-Generation Firewalls (NGFW)**: These combine traditional firewall capabilities with advanced features like intrusion prevention and application awareness to combat modern threats.

**5. Cloud Firewalls**: Deployed in cloud environments, these firewalls secure applications and data across virtual networks.

#### 2 type of firewall:
1. **hardware based:** 
   although(halaki) ASA is their classic firewall, modern ASAs include modern feature like "next generation firewall" including things like IPS or intrusion prevention system.
2. **software based** which are also called **host based firewall** are software application that filter traffic entering and existing a host machine like a PC.
### Gateway
Gateway is one of the network equipment that can **work at every layer** according to the OSI model. IT connect two 
- A gateway is a network node(device) that used to connect two dissimilar type of network or similar.
- Although it is similar to router devices in terms of its function, it differs from routers with its ability to work in every layer. In addition, there are **not only hardware but also software gateway** types. 
- *IT connect two network which has different protocol.*
- we can't access internet without gateway .
- IF your pc is connected to a switch so switch work as your gateway.

>so if your pc connected to a hub it on layer 1 and work as your gateway , if you connected to switch it on work as your gateway . if router than so on . like it can operate on all layer. as we know gateway is software and hardware based both.

Difficult to manage , low data transmission rate, expensive but provide some security.
### Access Points

**Wireless Access points (WAPs)** are the wireless network hardware devices that are used to send Wi-Fi signals for providing wireless connectivity to the wireless devices in a specified area.  They act as a bridge between wireless devices and the wired network infrastructure.

**Wireless Access point**:- A wireless access point (WAP or AP) is a device that allows wireless communication devices to connect to a wireless network using Wifi. Bluetooth or related standards. the WAP usually connect to a weird network (such as computer or printers) and wired devices on the network.
### NIC
NIC : **Network interface card**
- These are hardware components installed in computers that enable them to connect to a computer.
 - A network interface card is a computer hardware computer design to allow computer to communicate other a computer network it is both on OSI layer 1 and layer 2 device, as it provide physical access to networking medium and provides a low level address system through the use of mac address.

![[Pasted image 20241003215449.png]]

### Endpoints

Endpoints are also types of network hardware devices connected to the user ports of the switch in a computer network. **These devices are the ones who send and receive the data for the end users such devices include laptops, desktops, cameras, phones, etc.** 

The increasing use of end-user devices like laptops, mobile phones, etc. by organizations all over the world to access their resources / their network remotely is also increasingly exposing endpoints to cyber threats and attacks.
### Power over Ethernet (PoE)

PoE is a technology that provides power and data to the end network components in computer networks over the same ethernet cable.

With PoE, power-sourcing equipment (such as PoE switches) can deliver electrical power to PoE-enabled devices without the need for separate power cables.

### Benefits of Network Hardware Devices

Network hardware devices, such as routers, switches, firewalls, and access points, provide numerous advantages that enhance connectivity, security, and performance in computer networks:

**●** **Improved Connectivity**: Devices like routers and switches enable seamless communication between multiple devices and networks, ensuring efficient data transfer.

**●** **Enhanced Security**: Firewalls protect networks from unauthorized access and cyber threats by monitoring and controlling incoming and outgoing traffic.

**●** **Increased Scalability**: Network devices allow businesses to easily expand their network infrastructure to accommodate growth without significant reconfiguration.

**●** **Flexible Networking**: Wireless access points (APs) offer greater flexibility in device placement, eliminating the need for physical cables and allowing easy access from various locations.

**●** **Simplified Management**: Managed switches and routers provide centralized control over network settings, making it easier to monitor performance and troubleshoot issues.

**●** **Broader Coverage**: Wireless access points extend the range of a network, providing connectivity in larger areas and eliminating dead zones.

**●** **Support for IoT Devices**: Modern network hardware can accommodate the growing number of Internet of Things (IoT) devices, ensuring reliable connectivity and data management.