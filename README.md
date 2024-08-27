# VPC_public-private-subnets
**AWS project used in production **

**Demonstrates how to create a VPC that you can use for servers in a production environment**

To improve resiliency, you deploy the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer. 
For additional security, you deploy the servers in private subnets. 
The servers receive requests through the load balancer.
The servers can connect to the internet by using a NAT gateway. 
To improve resiliency, you deploy the NAT gateway in both Availability Zones.

**OVERVIEW**
The VPC has public subnets and private subnets in two availablity Zones
Each public subnet contains a NAT gateway and a load balancer node
The servers run in private subnets, are launched and terminated by using an autoscaling group, and receive traffic from the load balancer
The server can connect to the internet by using the NAT gateway 

**Steps**

