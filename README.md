# pfSense-Firewall-VM-Lab



## Objective



The objective of this home project is to set up a pfSense firewall within a virtualized environment using VMware and Kali Linux. The project involves configuring pfSense to secure network traffic, segment the network, and provide firewall protection for virtual machines. Kali Linux will be used to ensure that the firewall is set up correctly, validate that it is properly configured to control network traffic, and confirm that machines connected to the firewall can successfully reach each other and the internet. The goal is to create a secure, isolated network environment while gaining hands-on experience with firewall configuration, penetration testing, and network security validation. This was a pretty simple lab once she get the firewall and your computers on the same network you can login via the web console and configure any rules you would like 😎

### Skills Learned


-Firewall Configuration – Setting up and configuring pfSense as a network firewall to secure and manage network traffic.

-Virtualization – Using VMware to create and manage virtual machines for the pfSense firewall and Kali Linux.

-Network Segmentation – Implementing network segmentation for better security and isolation using pfSense.

-Troubleshooting & Validation – Ensuring the firewall is correctly configured and that connected machines can communicate securely across the network.

### Tools Used


-pfSense – Used for configuring the network firewall and managing traffic.

-VMware – Used for creating and managing virtual machines for pfSense and Kali Linux.

-Kali Linux – Used for network validation, ensuring proper connectivity, and performing tests on the firewall setup.

## Steps

1. Downloading Pfsense iso from pfsense.org

   ![Downloading Pfsense From Pfsense org](https://github.com/user-attachments/assets/c711e91c-e33a-4778-ab77-e20973352855)

2. Creating PfSense VM In VMware Workstation

   ![Creating PfSense VM In VMware Workstation](https://github.com/user-attachments/assets/202faf9d-d20e-46f0-8fa9-8005038eb2dd)

3. Setting Up Kali Linux To Configure Pf Sense From Web Browser

   ![Setting Up Kali Linux To Configure Pf Sense From Web Browser](https://github.com/user-attachments/assets/e1ff33f1-a0f4-452a-a47f-4b20c5ead0b9)

4. Setting the interface ip address so the firewall configuration can be reached from the web

   ![Setting the interface ip address so the firewall configuration can be reached from the web](https://github.com/user-attachments/assets/2e58d068-1138-4989-a517-78b0ebc05bd1)

5.The dhcp settings for the VM interface (Just wanted to show how I put the firewall and vm on the same network)

![The dhcp settings for the VM interface](https://github.com/user-attachments/assets/0c4d3145-51d7-4b54-9a7a-38013ae91b92)

6. Showing That Pfsense Can Be Accessed From Kali Linux

   ![accessing pfsense from kali linux](https://github.com/user-attachments/assets/ea72dd64-9325-4a04-b137-f32f663b0ff6)





