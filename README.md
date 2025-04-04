Design and simulate a network linking our ANU new campus getting into consideration that we have only two class C networks 
which are 193.158.1.0 and 2.0 covering specific number of hosts in 4 buildings and 
one server in a fifth building namely the data center building. All IP addresses are 
distributed in these 5 different locations with 4 different topologies in the four 
building networks. Each team shall select the topologies, implement them, sub-net 
them, protect them with NAT methods and try at least one routing methods to test 
their functionality of the network such as OSPF.  
 Project Tool: CISCO Packet Tracer 
  
 Project Requirements 
1. Select 4 different LAN network topologies and implement them on CISCO Packet
   
Trace (PT) with the following requirements: 
a. Each LAN shall be connected to one router.  
b. Each LAN shall contain at least the following: 
i. Bus shall contain at least 3 switches.  
ii. Ring / Token Ring contain at least 5 switches.  
iii. Tree contain at least 5 switches.  
iv. STAR topology contain only one switch.  
NB: LAN topology shall be illustrated on switches. 

c. At least one LAN shall contain Virtual LANs.

d. All LANs are sub-netted with class C IPs only in networks 193.168.1.0 & 

193.168.2.0 referring to the number of hosts as the following:  
i. Building A 
1. Number of Hosts: 212 Hosts 
ii. Building B 
1. Number of Hosts: 36 Hosts 
iii. Building C 
1. Number of Hosts: 47 Host 
iv. Building D 
1. Number of Hosts: 125 Hosts   
v. Data Center Building:  
1. Contains ONE server.
NB: These are the internal IP sub-netting for LANs.
e. All router external interfaces are chosen to be in the class A network 10.0.0.0.  

4. The server shall be added on a fifth network with the IP 172.125.12.9 (class B).  
NB: Connecting the 5 routers could be any topology chosen.

6. All IPs and subnet mask shall be documented in a table in the project report.  
7. Three types of NAT shall be illustrated as the following:  
a. PAT on the server LAN. 
8. One type of dynamic routing shall be illustrated in the project. It's recommend to choose 
the Open Shortest Path First (OSPF)  
