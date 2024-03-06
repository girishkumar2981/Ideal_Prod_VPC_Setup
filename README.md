# Ideal_Prod_VPC_Setup

Designed VPC with all necessary practices followed in Production and accessed a static web page running in private subnet using load balancer. The servers in private subnet can connect to the internet by using a NAT gateway.

# Steps Involved:

Create a VPC with all necessary configurations like Availability Zones, Routing table, Internet Gateway, NAT Gateway, Public and Private subnet, Application Load Balancer.

Create EC2 instances using Auto Scaling groups and make sure to create a launch template.

Deploy EC2 instances in the private subnet, for additional security.

Create a Bastian Host to connect with instances in private subnet. Make sure to copy the key pair from your local to bastian host.

Create a load balancer and a target group. Make sure to add the listener port of load balancer in the inbound rules of security Group.

Post, that you can access the application with load balancer DNS Name.










