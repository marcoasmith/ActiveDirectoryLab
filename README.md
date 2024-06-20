# Implementing Active Directory

The end goal of this home lab to set up Active Directory, including creating users and configuring the environment. Below are the key steps with corresponding screenshots.

## Step 1: Install Active Directory Domain Services

1. Open the Server Manager and navigate to `Add Roles and Features`.
2. Select `Active Directory Domain Services` and proceed with the installation.

![Install Active Directory Domain Services](path/to/screenshot1.png)

## Step 2: Configure Active Directory Domain Services

1. After the installation, promote the server to a domain controller.
2. Follow the wizard to create a new forest and domain (e.g., `mydomain.com`).

![Configure Active Directory Domain Services](path/to/screenshot2.png)

## Step 3: Create Organizational Units and Users

1. Open `Active Directory Users and Computers`.
2. Create a new Organizational Unit (OU) for users and admins.
3. Create new user accounts within the respective OUs.

![Create Organizational Units and Users](path/to/screenshot3.png)

## Step 4: Set Up DHCP Server

1. Open the Server Manager and navigate to `Add Roles and Features`.
2. Select `DHCP Server` and proceed with the installation.
3. Configure a new DHCP scope to allocate IP addresses.

![Set Up DHCP Server](path/to/screenshot4.png)

## Step 5: Join a Client to the Domain

1. On a client machine, open `System Properties` and change the computer name.
2. Join the computer to the newly created domain (e.g., `mydomain.com`).
3. Restart the computer and log in with a domain user account.

![Join a Client to the Domain](path/to/screenshot5.png)

## Summary

This project demonstrates the basic steps involved in setting up Active Directory, configuring DHCP, and joining a client to the domain. The steps outlined above ensure a functioning Active Directory environment for managing users and resources.

For detailed instructions and additional configurations, refer to the official Microsoft documentation.
