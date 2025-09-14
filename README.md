<p align="center">
<img width="1197" height="642" alt="image" src="https://github.com/user-attachments/assets/74e999ef-e43b-42b1-8635-48b9302ffaf5" />

</p>

<h1>Setting up a Virtual Machine and remote access</h1>
In this tutorial, we will set up Virtual Machines in Azure and utilize remote access. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 
- Windows Server 2022

<h2>Deployment and Congfiguring Steps</h2>


<h2>Actions and Observations</h2>

<p>
<img width="2098" height="1120" alt="Screenshot 2025-08-30 193458" src="https://github.com/user-attachments/assets/bd39f0cb-f496-400b-ae56-c5ef0f377565" />

</p>
<p>
Before you get started with creating Virtual Machines or VMs, you have to create an account with Aure. If you want to get the hang of Azure first, you could use a free subscription which will supply 200 dollars in free credit to use. Go to www.azure.portal.com to sign up with a email account and filling out the information prompts. After signing up, you will be presented with the home page where you have various options like creating VMs, resourse groups, storage accounts, etc.
</p>
<br />

<p>
<img width="2314" height="1176" alt="Screenshot 2025-08-30 193709" src="https://github.com/user-attachments/assets/93e80516-d323-4677-9f13-37b603a987dc" />

</p>
<p>
We are going to first create a resource group. You could click resource group on the front page or search it in the search bar on top.
</p>
<br />

<p>
<img width="1882" height="1220" alt="Screenshot 2025-08-30 194238" src="https://github.com/user-attachments/assets/edb70906-4091-4e08-a0cf-6e39bcd73eb2" />

</p>
<p>
On this page, make sure the subscription is on the free one that was created--> For the name, you can name it whatever you want but make sure that is the name used for the VMs--> and select the region. For this tutorial, East US 2--> Then click review and create.
</p>
<br />

<p>
<img width="1938" height="1184" alt="Screenshot 2025-08-30 194414" src="https://github.com/user-attachments/assets/ea535312-b1a6-4f09-a645-b29ae7bf6eb0" />
<img width="1732" height="852" alt="Screenshot 2025-08-30 201004" src="https://github.com/user-attachments/assets/6fe4da32-895d-4683-9c08-556c209e3b4d" />




</p>
<p>
Go to the VM page click create-->select the correct subscription--> Resource group, select the one we have created--> VM name, create a name--> Region, select the same region previously (East US 2)--> Then click review and create.
</p>
<br />

<p>
<img width="1880" height="922" alt="Screenshot 2025-08-30 201309" src="https://github.com/user-attachments/assets/ac6cef69-728d-43b1-93d1-ada1665b2159" />



</p>
<p>
For image, select Windows 10 Pro, version 22H2 - x64 Gen2--> Size, Satndard_D2s_v3- 2 vcpus, 8 GiB memory--> Administrator account, create username and password--> check off the licensing box--> click review and create.
</p>
<br />

<p>
<img width="1686" height="1244" alt="Screenshot 2025-08-30 201707" src="https://github.com/user-attachments/assets/073371f5-4661-4d11-b095-f8011b45fba4" />

</p>
<p>
On this page, click on the VM we just created and this is the page where you can locate the IP address of the VM.
</p>
<br />

<p>
<img width="1894" height="1268" alt="Screenshot 2025-08-30 202342" src="https://github.com/user-attachments/assets/a410d1d1-df0f-46f6-8b25-44e7c32fd971" />

</p>
<p>
Next, we are going to use the program, Remote Desktop Connection, to connect to the VM. Obatin the IP address by either scrolling right on the VM page near the VM or click on the VM itself.
</p>
<br />

<p>
<img width="804" height="456" alt="Screenshot 2025-08-30 202454" src="https://github.com/user-attachments/assets/69c49914-86e0-4e87-8f4e-53921827a2c7" />

</p>
<p>
Copy and paste the IP address and click connect. Enter the credentials. The username and password when we were setting up the VM.
</p>
<br />

<p>
<img width="780" height="538" alt="Screenshot 2025-08-30 202551" src="https://github.com/user-attachments/assets/47f8125c-ae91-489d-81c9-5e4b9d892bc8" />
<img width="2000" height="1124" alt="Annotation 2025-08-31 002901" src="https://github.com/user-attachments/assets/8122e9e4-de72-41b2-955d-862408131d92" />
You should be able to connect to the VM afterwords. This is the end of the tutorial. Utiling these steps will help with other tutorials like deploying active directory, installing OS ticketing system, and testing protocols like SSH, DHCP, RDP, DNS, etc
