# Network-Computers
# Mininet Topology Setup and Virtual Switch Configuration

## Virtual Switch Configuration

The `project1` file includes steps for setting up a virtual switch to manage traffic between hosts. The switch is connected to the external network to allow for communication beyond the Mininet simulation environment.  
In this project,  I also utilized Wireshark to analyze control packets within the network, providing deeper insights into data flow and network behavior.


## Project 2 Overview

The project explores the creation of different network topologies using Mininet, including star, linear, and tree topologies. Additionally, a more complex custom topology with 15 hosts and 10 switches was implemented.

## Topologies Implemented

1. **Star Topology**  
   A central switch connects directly to all hosts, ensuring a simple yet effective structure for testing point-to-multipoint communication.

2. **Linear Topology**  
   Hosts are connected in a straight line, with each host linked to the next via a switch. This topology is useful for simulating sequential data transfer across nodes.

3. **Tree Topology**  
   A hierarchical structure where switches and hosts are organized in layers, resembling a tree. This topology is ideal for scenarios mimicking real-world enterprise networks.

4. **Custom Topology (15 Hosts, 10 Switches)**  
   This custom topology involves a more complex design where 15 hosts are distributed across 10 switches. The setup aims to test network performance, routing, and scalability within Mininet.  

I also used Wireshark to examine SDN packets, enhancing the understanding of software-defined networking protocols.



