<p align="center">
<img width="230" height="141" alt="image" src="https://github.com/user-attachments/assets/a8281f77-8667-4a34-aa15-d69ebf24d29c" />
</p>

<h1>Creating Virtual Machines in Azure</h1>
This tutorial outlines the process and installation of Windows and Linux Virtual Machines in Azure.<br />


<h2>Video Demonstration</h2>

- ### [Youtube: Creating Windows and Linux Virtual Machines](https://www.youtube.com/watch?v=ISIau7bI14E) 

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows (Windows 10 Enterprise)
- Linux (ubuntu 22.04)

<h2>List of Prerequisites</h2>

- Register account in Azure
- Create a Resource Group
- Create Windows Virtual Machine
- Create Linux Virtual Machine


<h2>Installation Steps</h2>
You must register for an Azure account in order to construct virtual machines. Examine the various alternatives that best fit your company or the projects you are working on. After creating your account you can create a Resource Group. First you have to create Resource Group, to start you can click in the search bar or click <img width="47" height="16" alt="image" src="https://github.com/user-attachments/assets/03be3787-9799-43fe-8ada-89b456bab4c3" />

<p>
<img width="729" height="365" alt="Screenshot 2025-11-25 103136" src="https://github.com/user-attachments/assets/2fe6ccb2-6539-47d6-a0bd-76661ec2c056" />
  
You can name your Resource group whatever you want. 
  <p align left>
<img width="443" height="271" alt="image" src="https://github.com/user-attachments/assets/a6cf9e79-f10e-4eb8-bc5b-4b48251c9ac9" />
<p align left>
Click on <img width="224" height="28" alt="image" src="https://github.com/user-attachments/assets/a2fd8b2f-071d-435e-b44c-522b394aba35" />

Click on Create button at the bottom of the page
<p align left>
  <img width="251" height="438" alt="image" src="https://github.com/user-attachments/assets/a64a782d-a122-4dda-b622-e32373f7305e" />

After created the Resource Group, come back to your dashboard and click on Resource Group
<p align left>
<img width="803" height="376" alt="Screenshot 2025-11-25 122156" src="https://github.com/user-attachments/assets/870976e3-abd7-4c13-b946-1122185697e2" />
And you have your Resource Group created.
<p aling left> 
<img width="800" height="293" alt="image" src="https://github.com/user-attachments/assets/d803b3d7-0359-4e5e-b803-05c1b4dced82" />

After created the Resource Group you can continue with the second step which is creating a Virtual Machine, to do that you can click again the search bar and look for Virtual Machines or in the dashboard click on Virtual Machines.
<p align left>
<img width="586" height="203" alt="Screenshot 2025-11-25 123544" src="https://github.com/user-attachments/assets/429c2ec6-fb03-4ac5-826e-e3c874c3e540" />

Choose the first option
<p align left> 
<img width="686" height="386" alt="Screenshot 2025-11-25 123917" src="https://github.com/user-attachments/assets/85acb37f-f7e0-42f5-b547-0f214d793d70" />

Put in the appropriate subscription, in the resource group (RG-Network-Activities) click on the one you just created, Choose a name for your Virtual Machine (windows-vm in this case), for Region choose the same you use in the Resource Group, for Image use Windows 10 Enterprise, version 22H2 - x64 Gen2 
</p>

<img width="350" height="430" alt="Screenshot 2025-11-25 131103" src="https://github.com/user-attachments/assets/54a4c1c8-e74f-47a7-85a6-e534a3028954" />

For size try to use 2vcpus for a faster deployment, create a username and password for the Virtual Machine and always make sure to click in Licensing

<img width="311" height="326" alt="Screenshot 2025-11-25 132238" src="https://github.com/user-attachments/assets/03308153-0eea-4e95-97cd-f374847e0be9" />

Then click next for Disks
<p align left>
<img width="311" height="326" alt="Screenshot 2025-11-25 132238" src="https://github.com/user-attachments/assets/3e668943-9da0-42da-9ab7-167e8dc161d0" />


Click next for Network, then click on Review + Create 
<p align left>
<img width="393" height="455" alt="Screenshot 2025-11-25 133817" src="https://github.com/user-attachments/assets/6828c53e-21a4-460a-944f-655a575b8e18" />

After validation passed, click on Create at the bottom of the page to initialize deployment of the Virtual Machine

<p align left>
<img width="451" height="454" alt="Screenshot 2025-11-25 134704" src="https://github.com/user-attachments/assets/413c969e-8f81-45de-a779-148ac91090c5" />

When deployment has been completed go to Resources

<p aling left>
<img width="460" height="224" alt="image" src="https://github.com/user-attachments/assets/e424c634-6098-45a6-8fc9-759c13c88aa2" />

Once completed you can go to Resources and find the public IP address that will be use to check traffic between the 2 Virtual Machines, using Remote Desktop Connection (RDP)

<p align left>
<img width="582" height="189" alt="Screenshot 2025-11-25 143654" src="https://github.com/user-attachments/assets/de627f54-4cc8-4702-a528-a973bd6fa266" />

Virtual Machines in Windows and Linux has been created and are ready to test the traffic.

<p aling left>
<img width="508" height="139" alt="image" src="https://github.com/user-attachments/assets/91dde449-5da4-412a-b81a-1df8dd213e72" />



<br /># creating-vms
