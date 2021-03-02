---
layout: posts
tags: ["tcp/ip", "cybersecurity"]
---



[TOC]

# TCP/IP

## Theory of TCP/IP Protocols

```

```



The TCP/IP protocol is alternative architectural representation to the osi model , which will be covered in another post. The focus of this post is to introduce the theoretical concept, the components of this architectural model and having a basic idea on what specifically is affected on a given layer according to the principles of cybersecurity.

The TCP/IP layers are four, each one having a critical role in the model:

| application   |
| ------------- |
| **transport** |
| **INTERNET**  |
| **network**   |

What is the responsibility of each layer?

- Application: in this layer most application-related protocols and services are provided like routing protocols and host configuration (examples: HTTP, FTP, DHCP, SMTP), including libraries and application programming interfaces. 
- Transport: establishment of data channels and task-specific information exchange such as host-to-host connectivity, some being connectionless like UDP and connection-oriented like TCP; examples of issues that are resolved in this layer are: error control, segmentation, flow control, congestion control and port numbers;
- Internet: sending data from source to destination address through a process called Routing (IP Routing); the address is identified via the IP and this layer is responsible for exchanging data from other upper protocols identifiable from a unique protocol number; two IP versions: IPv4 and IPv6
- Link: within local network to which host is attached; size depends on networking hardware design; processes for which transmitting and receiving packets controlled by device driver, as well as firmware and or special chips; transmit frames to physical layer;



## The Encapsulation Process 

