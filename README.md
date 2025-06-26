# VPC
**What is vpc?**

 A VPC is a logically isolated section of the cloud where you can launch your resources and applications. It acts as a virtual network, allowing you to control access to your resources and manage the flow of data between them. VPCs provide the ability to host multiple isolated networks in the same cloud region, each with its own IP address space, routing tables, security groups, and network gateways.
 
# VPC Components

To understand VPC, it's important to understand the different components that make it up.

**Subnets**: A subnet is a range of IP addresses within a VPC, used to logically segment your network. Subnets are used to organize resources, such as instances and storage, into separate and isolated networks.

**Route Tables**: A route table contains a set of rules that determine where network traffic is directed. Each subnet in a VPC is associated with a route table, which controls the traffic routing between the subnet and other network destinations.

**Security Groups**: A security group acts as a virtual firewall for your instances, controlling inbound and outbound traffic. Security groups can be associated with one or more instances and are used to control access to your resources.

**Network Gateways**: A network gateway is a highly available VPC component that allows communication between your VPC and other networks, such as the internet or another VPC. Network gateways include Internet Gateways, Virtual Private Gateways, and VPN Connections.

**NAT Gateway**: A NAT gateway is a Network Address Translation (NAT) service. You can use a NAT gateway so that instances in a private subnet can connect to services outside your VPC but external services cannot initiate a connection with those instances.

**Internet Gateway**: Internet Gateway is a VPC component that allows communication between your VPC and the Internet.

# Practical steps involved in vpc:-

# Step 1:- Vpc Creation

![Image Alt](https://github.com/revathicse92/VPC/blob/86954da4f2bb80f7932bf83dc504ad759ce97eab/VPC%20SCREENSHOT/VPC-CREATION.PNG) 

# Step 2:- Subnet Creation

![Image Alt](https://github.com/revathicse92/VPC/blob/c50b40ca23f62685a245c3b869d6c62ebeb968cb/VPC%20SCREENSHOT/SUBNET%20CREATION.PNG) 

# Step 3:- Route Table Creation

![Image Alt](https://github.com/revathicse92/VPC/blob/c50b40ca23f62685a245c3b869d6c62ebeb968cb/VPC%20SCREENSHOT/ROUTE%20TABLE%20CREATION.PNG)   

# Step 4:- Internet Gateway Creation

![Image Alt](https://github.com/revathicse92/VPC/blob/01086b26b4f2db117cffb1d4dc2f68dd65ba0fce/VPC%20SCREENSHOT/INTERNET%20GATEWAY.PNG) 

# Step 5:- Security Group Creation

![Image Alt](https://github.com/revathicse92/VPC/blob/01086b26b4f2db117cffb1d4dc2f68dd65ba0fce/VPC%20SCREENSHOT/SECURITY%20_GROUP.PNG)  

# Step 6:- Windows and Linux Machine Creation

![Image Alt](https://github.com/revathicse92/VPC/blob/01086b26b4f2db117cffb1d4dc2f68dd65ba0fce/VPC%20SCREENSHOT/PRIVATE_WIN_SERVER.PNG)

![Image Alt](https://github.com/revathicse92/VPC/blob/01086b26b4f2db117cffb1d4dc2f68dd65ba0fce/VPC%20SCREENSHOT/PUBLIC%20AND%20PRIVATE%20LINUX%20SERVER.PNG)    


# Step 7:- Connecting with windows and Linux 

![Image Alt](https://github.com/revathicse92/VPC/blob/01086b26b4f2db117cffb1d4dc2f68dd65ba0fce/VPC%20SCREENSHOT/WINDOWS%20SERVER%20CONNECT%20WITH%20RDP.PNG)   

![Image Alt](https://github.com/revathicse92/VPC/blob/01086b26b4f2db117cffb1d4dc2f68dd65ba0fce/VPC%20SCREENSHOT/LINUX%20MACHINE%20CONNECT%20WITH%20PUTTY.PNG) 


  
  
