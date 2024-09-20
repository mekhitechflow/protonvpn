![image](https://github.com/JasonDelahoussaye/Virtual_Private_Network_VPN_IP_Address_Observations/assets/106440235/8feba822-22ed-4a5b-a709-b4383184314e)


<h1>Observing the Effect of a VPN on IP Addressing</h1>
In this project, I observed the impact of a virtual private network (VPN) on IP address, location, and web browsing.  The video will guide you visually through the steps involved and then further on there are some notes and screenshots provided for highlights of some or all of the material.<br />

<h2>Video Demonstration</h2>

- COMING SOON...
  
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
-	Remote Desktop
-	ProtonVPN (free version)


<h2>Operating System Used </h2>

- Windows 10 (21H2)

# Lab Tutorial: Setting Up VPN in an Azure Virtual Machine

## Objective
Gain a better understanding of VPNs by setting up a Virtual Private Network inside an Azure virtual machine. This lab will explore the impact of VPNs on IP addresses and locations.

## Step-by-Step Guide

1. Start by accessing the website "whatismyipaddress.com" on your actual PC. Take note of your public IP address and the corresponding city.

2. Create a virtual machine in Azure and establish a connection to it using Remote Desktop Protocol (RDP). This connection bridges your PC and the Azure virtual machine.

3. Within the Azure virtual machine, visit the website "whatismyipaddress.com" once again. This time, note down the new IP address and location. It should differ from your actual PC's IP address.

4. Sign up for the free version of ProtonVPN on your PC. Download and install the ProtonVPN client.

5. Inside the Azure virtual machine, connect to a ProtonVPN server located in the Netherlands (or another available country). This establishes a VPN connection between the virtual machine and the chosen ProtonVPN server.

6. Access the website "whatismyipaddress.com" again from within the Azure virtual machine, with the VPN active. Take note of the new IP address and location displayed. This IP address should reflect the location of the VPN server (e.g., ______, Netherlands).

By following these steps, you will have three entries in your text file representing different IP addresses and locations:

1. IP address and location from your actual PC without using a VPN.

<img width="1429" alt="Screenshot 2024-09-19 at 11 17 47 PM" src="https://github.com/user-attachments/assets/20e0542b-1555-4260-9214-4bc3d01cd6cd">
[Screenshot Here: PC IP Address]

4. IP address and location from the Azure virtual machine without using a VPN.

<img width="1416" alt="Screenshot 2024-09-19 at 10 36 51 PM" src="https://github.com/user-attachments/assets/8ccf1cc5-9a94-44fb-805b-2acd657a6d32">
[Screenshot Here: Azure VM IP Address]

6. IP address and location from the Azure virtual machine with the VPN connected to a ProtonVPN server in the Netherlands.
<img width="943" alt="Screenshot 2024-09-19 at 11 08 34 PM" src="https://github.com/user-attachments/assets/5d34423e-12c4-4d94-83cf-41956123070b">
<img width="1430" alt="Screenshot 2024-09-19 at 11 11 14 PM" src="https://github.com/user-attachments/assets/7ba1a78d-d1a3-42f6-9013-10aa02fc8838">
[Screenshot Here: VPN IP Address].
I know the picture above doesn't show a city/region within the Netherlands, this has more to do with the website https://whatismyipaddress.com/ not getting it correct. Yours may do this as well for the sake of the tutorial the purpose is to show that by using proton VPN you are able to get a new IP address somewhere else in the world. This allows you to appear as if you're browsing from a different country, which can provide benefits such as enhanced privacy, accessing geo-restricted content, or safeguarding your data when using public Wi-Fi. However, it's important to note that IP geolocation services may not always be 100% accurate, so your IP address might be associated with a nearby region rather than the exact country you selected. Despite this, Proton VPN still effectively masks your real location and encrypts your internet traffic to keep your online activity private and secure.

## Understanding the Results

From this exercise, you can observe the following:

- When accessing the website from your actual PC without a VPN, it shows your original IP address and your city location.

- After connecting to the Azure virtual machine and accessing the website, a different IP address and the location of the virtual machine (e.g., Paris) are displayed.

- Finally, by connecting to the ProtonVPN server in the Netherlands from within the virtual machine and accessing the website again, another IP address and the location of the VPN server (e.g., _______, Netherlands) are shown.

This exercise demonstrates how VPNs work by encrypting and routing your internet traffic through remote servers, making it appear as if you are browsing from different locations. VPNs can enhance privacy, and security, and allow you to bypass geo-restrictions.
