Q1 Create a hybrid topology in Packet Tracer by combining elements of mesh, bus, and ring topologies. Use two switches (Switch M, Switch N), 10 PCs, and 3 hubs to design the hybrid topology. Assign IP addresses to the PC. Make sure any two Pc should be able to send email to each other. 

Q2 Create a network topology with 5 routers and four networks. Configure static routes using commands on each router to enable communication between all networks. 
Network A 129.10.0.0, 
Network C 111.0.0.0,
Network B 200.100.0.0 and 
Network D 199.99.109.0

Q3 Make a communication possible between five different branches representing through different networks of a company. HTTP Server is arranged in network 4. Network 1 is with network id as 171.12.0.0 and network 2 is with 172.12.0.0 and network 3 is of network id 192.123.192.0. Network 4 is of subnet mask 255.255.0.0. Network 5 has total 254 hosts. All systems of network 1 to 3 can communicate to servers using static routing. Whole setup is with 5 routers.

Q4 Make the communication possible between five different branches representing through different networks of a company. HTTP Server is arranged in network 4. Network 1 is with network id as 171.12.0.0 and network 2 is with 172.12.0.0 and network 3 is of network id 192.123.192.0. Network 4 is of subnet mask 255.255.0.0. Network 5 has total 254 hosts. All systems of network 1 to 3 can communicate to servers using dynamic routing. Whole setup is with 5 routers.


05 Using Packet tracer, create a Star topology and establish connectivity among them ensure 
connectivity using three routers in between these networks using ping command. The topology should
contain at least 4 PCs. Create required subnets from the network 83.23.10.0/16. Host requirements are
as SNI= 44 SN2= 31 SN3=9 SN4= 21

Q6 Using Packet Tracer, create a Star topology and establish connectivity among them. Ensure
connectivity using three routers in between these networks using ping command. The topology should
contain at least 4 PCs. Create required subnets from the network 83.23.10.0/16. Host requirements are
as SNI=44 SN2= 31 SN3=9 SN4= 21

 Q7 Create separate star topology and bus topology and connect it to three separate interconnected router and perform static routing. Create subnets from the network 59.62 13.0/16 SN1: 313 SN2:19 SN3:5000 to configure the scenario. 

Q8 Perform static routing for networks enabled with ipv6 addressing.

 Q9 Perform dynamic routing for networks enabled with ipv6 addressing

Q10 You are setting up a small office network for a startup company. The office has four departments: Sales (2), Marketing(2), Finance(3), and IT(4). Each department need to be connected to the network. Design a suitable network topology using Cisco Packet Tracer.

Requirements:

1. Each department should have its own dedicated network segment.

2. All departments should have internet access through a central router. You can use any combination of topologies (e.g., Bus, Star, or Tree) to fulfill the requirements. Design the topology





Addressing each question:

### Q1:
For a hybrid topology combining mesh, bus, and ring:

```plaintext
Switch M
|
Hub 1 ---- PC1
|
Hub 2 ---- PC2
|
Hub 3 ---- PC3
|
Switch N
|
Hub 4 ---- PC4
|
Hub 5 ---- PC5
|
Hub 6 ---- PC6
|
Hub 7 ---- PC7
|
Hub 8 ---- PC8
|
Hub 9 ---- PC9
|
Hub 10 ---- PC10
```

### Q2:
For a network topology with 5 routers and four networks:

```plaintext
Network A: 129.10.0.0
Network B: 200.100.0.0
Network C: 111.0.0.0
Network D: 199.99.109.0
```

### Q3:
For communication between five branches using static routing:

```plaintext
R1 ---- N1 ---- R2 ---- N2 ---- R3 ---- N3 ---- R4 ---- N4 (HTTP Server) ---- R5
```

### Q4:
For communication between five branches using dynamic routing:

```plaintext
R1 ---- N1 ---- R2 ---- N2 ---- R3 ---- N3 ---- R4 ---- N4 (HTTP Server) ---- R5
```

### Q5/Q6:
For a star topology with three routers connecting four networks:

```plaintext
    R1
    |
    N1
    |
    R2
 /--|--\
N2 N3 N4 N5 (HTTP Server)
```

### Q7:
For separate star and bus topologies with static routing:

```plaintext
Star Topology                 Bus Topology
    |                             |
Router 1 ---- N1               Router 2
    |                             |
Router 3 ---- N2               Router 4
    |                             |
Router 5 ---- N3               Router 6
```

### Q8:
For static routing with IPv6:

Set up static routes on routers using IPv6 addresses.

### Q9:
For dynamic routing with IPv6:

Use a dynamic routing protocol (e.g., OSPFv3) on routers for IPv6.

### Q10:
For a small office network with four departments:

```plaintext
               Internet
                 |
               Router
 /----/--------|--------\----\
Sales  Marketing  Finance  IT
(2)    (2)        (3)      (4)
```

This topology connects all departments to a central router for internet access. The specific addressing and configuration details depend on the requirements and constraints.
