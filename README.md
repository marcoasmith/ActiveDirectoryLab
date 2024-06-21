# Implementing Active Directory

The end goal of this home lab to set up Active Directory, including creating users and configuring the environment. Below are the key steps with corresponding screenshots.

## Step 1: Download and Install Resources

1. Download and install Oracle VirtualBox 
2. Download Windows 10 and Server 2019 ISOs

![Install Active Directory Domain Services](https://i.imgur.com/Yugllvp.png)

## Step 2: Create and Configure VM for DC

1. Create a virtual machine for the domain controller 
2. Configure network settings
3. Install Server 2019 on the Domain Controller virtual machine 

![Configure Active Directory Domain Services](path/to/screenshot2.png)

## Step 3: Set up IP addressing for NICs 

1. Domain controller VM has two NICS from configuratiom
2. One has IP address automatically given using DHCP
3. Assign IP address to internal NIC
   
   

![Create Organizational Units and Users](https://i.imgur.com/grNwz5p.png)

## Step 4: Install Active Directory and Create Domain

1. Choose server to install active directory
2. Add a new forest to create domain


![Set Up DHCP Server](https://i.imgur.com/mkj2jok.png)

## Step 5: Install RAS/NAT

1. Allows client to be on virtual network
2. Allows client to access interent through domain controller 


![Join a Client to the Domain](https://i.imgur.com/uKF9WaM.png)



## Step 6: Set up DHCP server for Clients

1. Allows client to get an IP address automatically 
2. Scope was set for IP address given to clients
   

![Join a Client to the Domain](https://i.imgur.com/klK5MLS.png)


## Step 7: PowerShell Script

1. Use a powershell script to create multiple user accounts in Active Directory
2. Allows users to access domain and resources
   

![Join a Client to the Domain](https://i.imgur.com/Yhd3pVf.png)

## Step 8: Create Client VM

1. Create and configure client VM
2. Use Windows 10 ISO file
3. Choose internal network adapter
   
## Step 9: Client machine to Domain 

1. Join the client machine to the domain
2. Log in to the client machine using a domain user account 




![Join a Client to the Domain](https://i.imgur.com/O7So2XT.png)

## Summary

This project demonstrates the basic steps involved in setting up Active Directory, configuring DHCP, and joining a client to the domain. The steps outlined above ensure a functioning Active Directory environment for managing users and resources.

