<p align="center">
    <img src="https://www.imagar.com/wp-content/uploads/2018/06/azure.png" width="300"/>  
</p>

<h1>Set Up VPN within Microsoft Azure VMs</h1>
<h2>Objective</h2>
<p>
  In this turorial, setting up a Virtual Private Network (VPN) in Microsoft Azure involves creating a Virtual Network, configuring a Gateway Subnet, and then creating a VPN gateway to establish a secure connection between your on-premises network and your Azure virtual network. Here are the steps to set up a VPN using Microsoft Azure.
</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- RD Client App

<h2>Operating Systems Used</h2>

- Windows 10 Pro (Virtual Machine)

<h2>Step-by-Step Guide</h2>

- Step 1
- Step 2
- Step 3
- Step 4
- Step 5
- Step 6

<h2>Deployment and Configuration Steps</h2>

<h3>Step 1</h3>
<p>
  In Microsoft Azure, create a Resource Group based on where you live or your preference of state or country. Then, name your group before you create it.
</p>

<img width="956" alt="78998FBB-276B-4C69-B47A-EAD7D989FD6C" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/f64f81ea-b908-42ff-ae10-9d6eebdd46a3">

<br />

-----
<h3>Step 2</h3>

<p>
  Create a Windows 10 Virtual Machine in another geographic location (try a different country). Do not forget to take note of the login you create for the next step, including the Public IP Address in the VM you have created.
</p>

<img width="956" alt="B1F2DD03-94B2-444F-8C66-CBEBE7279DE8" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/3ecd2b22-aeb6-4299-b496-a8cdac8ee93f">

<img width="956" alt="2EF5A1CA-0ED3-4BB1-A2AF-06B2C8B9B65F" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/2ee6cb5e-b869-4c11-9d98-33522f845736">

<br />

-----
<h3>Step 3</h3>

<p>
  Log into the RD Client App with the Public IP Address and the login you created.
</p>

<img width="956" alt="FC5AB73B-4245-4F1B-927D-FFA4379AB7FC" src="https://github.com/anumkhanit/vpn-config/assets/144633389/9c3850e5-460b-42c6-b954-79d6ad372c04">

![60D11E2F-2D69-47B1-835F-CAA9CDD4D0A2](https://github.com/anumkhanit/vpn-config/assets/144633389/9d8f30ef-558f-4f86-8525-762b5f2103c3)

<br />

-----
<h3>Step 4</h3>

<p>
  On your Virtual Network (Windows 10 Pro). Browse to https://whatismyipaddress.com/ and note the IP address based on the chosen location you previously created on Microsoft Azure.
</p>

<img width="750" alt="D6C23742-09CB-4461-BB63-19F81B989ED4" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/fdf414e8-416e-46f6-8ec4-172a6e4aa55d">

<br />

-----

<h3>Step 5</h3>

<p>
  Back to your actual computer, head to https://protonvpn.com. Create the account (make sure you use the free subscription since you will be limited to three countries).
</p>

<img width="750" alt="2599D3A1-EA52-435C-B781-20CDD91E13A4" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/fd750503-8a15-4e2c-80df-4c2758514bf1">

<br />

-----

<h3>Step 6</h3>

<p>
 A) Back to your VM, head to https://protonvpn.com, login, and download the Windows VPN and follow through installation.
</p>

<img width="750" alt="26862F4E-93E9-42A2-8CD0-723CE288C096" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/27ce83d7-d43b-491e-a707-2d70c30608cc">

<img width="750" alt="A93FA32C-B569-45B1-A93F-1DFCAE33FC86" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/a6aa9621-f50b-4f6d-bc1f-798ac2901530">

-----

<p>
  B) Login to the VPN you have downloaded.
</p>

<img width="680" alt="68842738-5213-4160-8279-95639D9F75AC" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/ce1d29b6-fffb-47de-a833-1d71a81289d9">

-----

<p>
  C) Once you login, you have three countries available (for free only). Choose Japan and connect and let it run through.
</p>

<img width="956" alt="CD9F61B9-7328-4907-95B3-DCEE71E4D8DF" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/c3e0499d-b7e6-4f9f-8c6f-3a67ab58ba90">

<img width="956" alt="FD00EE0B-3E0C-43E0-96AD-A6B5B1F2F1F5" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/174b8660-35d6-4142-ae4b-21f3c897025a">

-----

<p>
  D) Since you are connected (virutally) in network by choosing Japan. You notice the IP is different than the previous IP Address from Step 4. Without the virtual network from Microsoft Azure to connect virtually in Windows 10 Pro or beyond, it wouldn't make a difference unless if you own Windows or MacOs. You can still download Proton VPN (for free otherwise you have to pay either monthly or annually depend on your needs).
</p>

<img width="956" alt="0DD5224D-2E62-4A52-A90F-7E6D6C834CD6" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/07b6c1b2-f461-459b-af91-43d35e341410">

-----

<p>
  E) Finally, when you pull up Google while being connected virtually with Windows 10 Pro and Proton VPN. You are 'connected' to Japan.
</p>

<img width="956" alt="0E4576D6-E4ED-49C9-B1C7-87889BBBB01F" height="30%" width="30%" src="https://github.com/anumkhanit/vpn-config/assets/144633389/541c9965-3c5d-4a7d-8a85-9b4708a2d8b6">

<br />

-----
<h2>Conclusion</h2>
Remember to follow security best practices and consider the specific requirements of your Azure environment and ProtonVPN subscription when configuring this setup. It's also important to ensure that you comply with both Azure and ProtonVPN's terms of service and security guidelines.
