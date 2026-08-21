# Networking Fundamentals

> **Course:** Networks & Communication
> **Topic:** Networking Fundamentals
> **Date:** August 21, 2026

## What Is a Network?

A **network** is a group of connected devices that can communicate and share information or resources.

Examples of devices on a network include:

* Computers
* Phones
* Servers
* Printers
* Routers
* Smart devices

Networks allow devices to communicate with one another and access shared resources such as files, applications, printers, and the internet.

---

## Types of Networks

### PAN — Personal Area Network

A **Personal Area Network (PAN)** is a very small network centered around one person.

Usually covers roughly **10 meters or less**.

Examples:

* Phone connected to wireless earbuds
* Smartwatch connected to a phone
* Bluetooth devices

### LAN — Local Area Network

A **Local Area Network (LAN)** connects devices within a limited physical area.

Examples:

* Home
* Office
* School
* Building

LANs are commonly created using **Ethernet** or Wi-Fi.

### WLAN — Wireless Local Area Network

A **Wireless Local Area Network (WLAN)** is essentially a LAN that uses wireless communication instead of requiring every device to use a physical cable.

Example:

A laptop connecting to a home router through Wi-Fi.

### WAN — Wide Area Network

A **Wide Area Network (WAN)** connects networks across much larger geographic areas.

A WAN can connect networks across:

* Cities
* States
* Countries
* Continents

The **internet** is the largest example of a WAN.

Organizations may use WAN connections provided by an **Internet Service Provider (ISP)** to connect offices in different locations.

---

## Internet Service Provider (ISP)

An **ISP** is a company that provides access to the internet.

The ISP connects a customer's local network to larger networks that ultimately make up the internet.

---

## Latency

**Latency** is the delay between sending data and receiving it.

Lower latency = faster response.

Higher latency = longer delay.

Latency becomes especially noticeable with things like:

* Gaming
* Video calls
* Streaming
* Remote applications
* Cloud services

---

## Peer-to-Peer (P2P)

In a **peer-to-peer network**, devices communicate directly with one another.

There may not be a dedicated central server controlling the network.

P2P networks work well for:

* Small networks
* Simple file sharing
* Direct communication between devices

They become harder to manage as the network grows.

---

## Client-Server Networks

A **client-server network** uses servers to provide services or resources to client devices.

**Client:** Requests a resource or service.

**Server:** Provides the requested resource or service.

Example:

When a computer accesses a website:

`Client → Request → Server`

`Client ← Response ← Server`

Client-server architecture is easier to manage and scale than basic P2P networks, which is why it is common in businesses and cloud environments.

---

# How the Internet Works

## Data Is Broken Into Packets

When information travels across a network, the data is divided into smaller pieces called **packets**.

Instead of sending one giant block of data:

`Large Data → Packets → Network → Destination`

The destination device can reconstruct the packets into the original data.

---

## Packet Headers

Packets contain information that helps networking devices determine where the packet came from and where it needs to go.

A packet header can contain information such as:

* Source information
* Destination information
* Protocol information
* Other information needed to process the packet

Think of the header like the information written on an envelope.

---

## IP Address

**IP = Internet Protocol**

An **IP address** identifies a device/interface on an IP network and helps networking devices determine where packets should be delivered.

Think:

**IP address = Where should the packet go?**

Example IPv4 address:

`192.168.1.10`

---

## MAC Address

**MAC = Media Access Control**

A **MAC address** identifies a network interface at the local network/data-link level.

Think:

**MAC address = Which local network interface should receive the frame?**

IP addresses and MAC addresses perform different jobs but work together during network communication.

---

## Switches

A **switch** primarily connects devices within the same LAN.

It forwards Ethernet frames toward the correct device using **MAC addresses**.

Example:

`Computer → Switch → Printer`

Switches are especially important for communication between devices on the same local network.

---

## Routers

A **router** connects different networks.

Its job is to determine where IP packets should go next so they can reach their destination.

Example:

`Laptop → Router → Internet → Router → Server`

Routers primarily make forwarding decisions using **IP addresses**.

---

## DNS — Domain Name System

Humans prefer names such as:

`example.com`

Computers communicate using IP addresses.

The **Domain Name System (DNS)** translates domain names into IP addresses.

Conceptually:

`example.com → DNS lookup → IP address`

This allows users to remember website names instead of memorizing IP addresses.

---

## Packet Switching

The internet uses **packet switching**.

Data is divided into packets, and packets are forwarded through networking devices toward their destination.

Different packets can potentially take different paths depending on network conditions and routing decisions.

At the destination, the data can be reconstructed appropriately.

---

# How Everything Connects

A simplified example of opening a website:

1. My computer connects to my local network.
2. I enter a website's domain name.
3. DNS helps determine the website's IP address.
4. My device sends data in packets.
5. A switch may move traffic through my local LAN.
6. My router forwards traffic toward other networks.
7. My ISP provides connectivity to the wider internet.
8. Routers across networks forward packets toward the destination.
9. The server receives the request.
10. The server sends data back to my device.

---

# Key Terms

| Term        | Meaning                                               |
| ----------- | ----------------------------------------------------- |
| Network     | Connected devices that communicate                    |
| PAN         | Personal Area Network                                 |
| LAN         | Local Area Network                                    |
| WLAN        | Wireless Local Area Network                           |
| WAN         | Wide Area Network                                     |
| ISP         | Internet Service Provider                             |
| P2P         | Peer-to-Peer                                          |
| Client      | Device/software requesting a service                  |
| Server      | Device/software providing a service                   |
| Packet      | Small unit of data transmitted across a network       |
| IP Address  | Logical address used for IP communication and routing |
| MAC Address | Data-link identifier used on local networks           |
| Switch      | Connects devices within a LAN                         |
| Router      | Connects different IP networks                        |
| DNS         | Translates domain names into IP addresses             |
| Latency     | Delay in network communication                        |

---

## What I Learned

I learned that networks allow devices to communicate and share resources. Networks can range from small personal networks such as PANs to massive WANs such as the internet.

I also learned that internet communication depends on several technologies working together. Data is broken into packets, IP addresses help identify network destinations, MAC addresses are used for local network delivery, switches connect devices within LANs, routers move traffic between networks, and DNS translates human-readable domain names into IP addresses.

Understanding these fundamentals is important because cloud services ultimately rely on networking to allow users, servers, applications, and other resources to communicate.
