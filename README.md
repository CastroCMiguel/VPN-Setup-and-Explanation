<p align="center">
<img src="https://i.imgur.com/WdCgaTo.jpg" alt="1"/>
</p>

<h1>Observing the Effect of a VPN on IP Addressing</h1>

In this project, I conducted an investigation into the effects of a virtual private network (VPN) on IP addresses, geographical locations, and web browsing behavior. The accompanying video provides a visual walkthrough of the procedures involved, and following that, I've provided detailed notes and screenshots highlighting key aspects of the material.

<h2>Video Demonstration</h2>

- ### [Observing the Effect of a VPN on IP Addressing](https://www.youtube.com/watch?v=cQUW0sJink4)
  
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
-	Remote Desktop
-	ProtonVPN (free version)

<h2>Operating System Used </h2>

- Windows 10
  
<h2>Objective</h2>

Enhance your comprehension of VPNs by establishing a Virtual Private Network within an Azure virtual machine. This laboratory exercise is designed to delve into the effects of VPNs on IP addresses and geographical locations.

<h2>Deployment and Configuration Steps</h2>

1. Begin by accessing the website "whatismyipaddress.com" on your physical computer (PC). Make a record of your public IP address and the associated city.

2. Create a virtual machine in Azure and establish a connection to it using the Remote Desktop Protocol (RDP). This connection links your PC with the Azure virtual machine.

3. Inside the Azure virtual machine, revisit the website "whatismyipaddress.com." This time, make a record of the new IP address and location. It should be distinct from the IP address of your physical PC.

4. Register for the free version of ProtonVPN on your PC, and subsequently, download and install the ProtonVPN client.

5. Within the Azure virtual machine, establish a connection to a ProtonVPN server situated in Japan (or any other accessible country). This action creates a VPN link between the virtual machine and the selected ProtonVPN server.

6. While the VPN is active, once more, visit the website "whatismyipaddress.com" within the Azure virtual machine. Make a record of the new IP address and the displayed location. This IP address should correspond to the location of the VPN server (e.g., Tokyo, Japan).

Once you've completed these steps, you will have accumulated three entries in your text file, each signifying different IP addresses and their corresponding locations:

1. IP address and location from your actual PC without using a VPN.

<p align="center">
<img src="https://i.imgur.com/LBQ3BhJ.png" alt="1"/>
</p>

2. IP address and location from the Azure virtual machine without using a VPN.

<p align="center">
<img src="https://i.imgur.com/uX8kwuZ.png" alt="1"/>
</p>

3. IP address and location from the Azure virtual machine with the VPN connected to a ProtonVPN server in Japan.

<p align="center">
<img src="https://i.imgur.com/x7EYaGH.png" alt="1"/>
</p>

From this exercise, you can make the following observations:

- When accessing the website from your physical PC without using a VPN, it displays your original IP address and your city location.
- Upon connecting to the Azure virtual machine and accessing the website, it presents a different IP address along with the location of the virtual machine (e.g., Frankfurt, Germany).
- Ultimately, upon connecting to the ProtonVPN server in Japan from within the virtual machine and revisiting the website, a distinct IP address and the location of the VPN server (e.g., Tokyo, Japan) are revealed.

This exercise serves as a practical illustration of how VPNs operate by encrypting and redirecting your internet traffic through remote servers, thereby masking your true location. VPNs offer benefits such as improved privacy and security while also enabling you to circumvent geo-restrictions.
