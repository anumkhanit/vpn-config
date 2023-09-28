<p align="center">

![039365F1-2A46-4361-A58C-A7B41645AFBA_4_5005_c](https://github.com/anumkhanit/vpn-config/assets/144633389/f366ef03-84d3-498d-b487-652f8be8f216)

</p>

<h1>Exploring Virtual Machines and VPN</h1>
<p>In this tutorial, we will install a Virtual Private Network (VPN) in Microsoft Azure. It involves configuring a Network Subnet and VPN gateway to establish a secure connection between your on-premises and Azure virtual networks. There are some notes and highlights provided of some or all explanations.</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
-	MacBook Air
-	RD Client
-	ProtonVPN (free version)

<h2>Operating System Used </h2>

- Windows 10 Pro

-----

<h1>Part 1: Creating a Virtual Machine in Azure</h1>

- Visit https://whatismyipaddress.com/ and record your IP address in a text file for reference.

- Create a Resource Group.

<img width="700" alt="78998FBB-276B-4C69-B47A-EAD7D989FD6C" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/f64f81ea-b908-42ff-ae10-9d6eebdd46a3">

- Deploy a Windows 10 Virtual Machine in a different geographic location, preferably in a different country.

<img width="700" alt="B1F2DD03-94B2-444F-8C66-CBEBE7279DE8" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/3ecd2b22-aeb6-4299-b496-a8cdac8ee93f">
  
- Access the VM using RD Client after creating the VM Machine (with the login you created) and copy the Public IP Address above on the right.

<img width="700" alt="FC5AB73B-4245-4F1B-927D-FFA4379AB7FC" src="https://github.com/anumkhanit/vpn-config/assets/144633389/9c3850e5-460b-42c6-b954-79d6ad372c04">

![60D11E2F-2D69-47B1-835F-CAA9CDD4D0A2](https://github.com/anumkhanit/vpn-config/assets/144633389/9d8f30ef-558f-4f86-8525-762b5f2103c3)
  
- Visit https://whatismyipaddress.com/ again from the VM and record the new IP address in the text file.

<img width="700" alt="D6C23742-09CB-4461-BB63-19F81B989ED4" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/fdf414e8-416e-46f6-8ec4-172a6e4aa55d">

<br />

-----

<h1>Part 2: Setting Up ProtonVPN and Testing VPN Connection</h1>

- On your local computer, sign up for the free version of ProtonVPN at https://account.protonvpn.com/signup?plan=free&language=en.
Within your VM, download the Proton VPN client.

<img width="700" alt="2599D3A1-EA52-435C-B781-20CDD91E13A4" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/fd750503-8a15-4e2c-80df-4c2758514bf1">

<img width="700" alt="26862F4E-93E9-42A2-8CD0-723CE288C096" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/27ce83d7-d43b-491e-a707-2d70c30608cc">

<img width="700" alt="A93FA32C-B569-45B1-A93F-1DFCAE33FC86" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/a6aa9621-f50b-4f6d-bc1f-798ac2901530">

- Log in to the VPN client and select a VPN server in yet another country, like Japan.

- Visit https://whatismyipaddress.com/ from the VM and record the new IP address.

- Explore Google, Disney, and/or Amazon websites and note any differences, such as language or URL changes based on the VPN server's location.

-----

<h1>Conclusion</h1>
This portfolio guide helps you explore Azure Virtual Machines and VPN services. Remember to follow security best practices and consider the specific requirements of your Azure environment and ProtonVPN subscription when configuring this setup. 
