# Fastest

Suppose you are hired by a top-ranked ISP company called “Fastest”. Statistics show that in the next 10 years the number of customers will increase by four times. Now you are being assigned to design the network infrastructure for the company so that they don’t need to update anything for the next 10 years at least. Follow the instructions below to design the network infrastructure:
The company provides its services to six cities. The cities are:
<ol>a) Dhaka(512)</ol>
<ol>b) Gazipur(32)</ol>
<ol>c) Narsingdi(8)</ol>
<ol>d) Tangail(64)</ol>
<ol>e) Manikganj(16)</ol>
<ol>f) Munshiganj(256)</ol>
<br>
You must set up a router for each city and the routers must be configured in such a way that the routers support four times the number of hosts currently assigned.
Make sure that Tangail and Gazipur can communicate without human intervention.
Munshiganj, Manikganj, and Narshindhi must be connected with each other so that they can route among them 100% securely.
Dhaka should work as a connector between these two groups. Moreover, it works as a receiver of packets delivered to unknown IP addresses.
Gazipur and Narsindi must have a connection between them and this connection should only work if the Dhaka router stops working. Otherwise, every packet from Gazipur-Narsingdi should travel via Dhaka.
Remember that the default route can not be used while exchanging packets within the topology. Data will be delivered using static or dynamic routes only. 
While assigning IP addresses to Dhaka, you need to create a Server named “Distributor” which will assign IP addresses to host devices dynamically.
A web server named “BARI” should be connected with Gazipur which will display “Welcome to Gazipur”. 
Showing 2 end devices per network is good enough to represent the whole population.
You need to be able to ping each network from another after all the setups are complete.
