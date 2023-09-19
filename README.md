<p align="center">
  
</p>

<h1>Configuring Virtual Private Network Deployed in the Cloud (Azure)</h1>
Setting up a Virtual Private Network (VPN) in Microsoft Azure involves creating a Virtual Network, configuring a Gateway Subnet, and then creating a VPN gateway to establish a secure connection between your on-premises network and your Azure virtual network. Here are the steps to set up a VPN using Microsoft Azure<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Google Search
- RD Client App

<h2>Operating Systems Used</h2>

- Windows 10 Pro (Virtual Machine)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4
- Step 5
- Step 6
- Step 7
- Step 8

<h2>Deployment and Configuration Steps</h2>

<h3>Step 1</h3>
<p>
  Browse to https://whatismyipaddress.com/ and take note (usually IPv4) to remember the IP Address for creating your remote desktop app, RD Client.
</p>

<img width="750" alt="12C5FD5C-D7AA-48C2-8804-F692C7ED6AE2" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/b354854e-9218-474b-a7f6-ca072d601460">

<br />

-----
<h3>Step 2</h3>
<p>
  Create a Resource Group based on where you live or your preference of state or country. Then, name your group before you create it.
</p>

<img width="750" alt="78998FBB-276B-4C69-B47A-EAD7D989FD6C" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/f64f81ea-b908-42ff-ae10-9d6eebdd46a3">

<br />

-----
<h3>Step 3</h3>

<p>
  A) Create a Windows 10 Virtual Machine in another geographic location (try a different country). Do not forget to take note of the login you create for the next step, including the Public IP Address in the VM you have created.
</p>

<img width="750" alt="B1F2DD03-94B2-444F-8C66-CBEBE7279DE8" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/3ecd2b22-aeb6-4299-b496-a8cdac8ee93f">

<img width="750" alt="2EF5A1CA-0ED3-4BB1-A2AF-06B2C8B9B65F" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/2ee6cb5e-b869-4c11-9d98-33522f845736">

<br />

-----
<h3>Step 3</h3>

<p>
  B) Log into the RD Client App with the Public IP Address and the login you created.
</p>

<img width="715" alt="FC5AB73B-4245-4F1B-927D-FFA4379AB7FC" src="https://github.com/anumkhanit/vpn-config/assets/144633389/9c3850e5-460b-42c6-b954-79d6ad372c04">

![60D11E2F-2D69-47B1-835F-CAA9CDD4D0A2](https://github.com/anumkhanit/vpn-config/assets/144633389/9d8f30ef-558f-4f86-8525-762b5f2103c3)

<br />

-----
<h3>Step 3</h3>

<p>
  C) On your Virtual Network (Windows 10 Pro). Browse to https://whatismyipaddress.com/ and note a different IP address based on the chosen location you previously created on Microsoft Azure. Notice the difference!
</p>

<img width="750" alt="D6C23742-09CB-4461-BB63-19F81B989ED4" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/fdf414e8-416e-46f6-8ec4-172a6e4aa55d">

<br />

-----
