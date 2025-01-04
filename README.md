# virtualmachinesconfig

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Server Manager

<br>

<h2>Operating Systems Used </h2>

- Windows 10 Pro, version 22H2


</b>
<br>
<h2>List of Prerequisites</h2>

- Azure Tenant and Subscription

</br>

<br>

<h2>Configuration and Deployment Steps</h2>

<p align="left"> Step 1. Create a resource group inside Microsoft Azure</p>
<p> > Once login to Azure, you'll see the landing page. It is from here where you'd be able to locate the different services that Azure has to offer. </p>
<p> > You could either search for *Resource Groups in the search engine at the top of the page or click on the shortcut. </p>
<p> > Once on the Resource Group landing page, you're going to go to *Create </p>
<p align="center">
<img src="https://github.com/user-attachments/assets/6d46ff79-29c5-4cfb-8b7a-ea801e5f0c77" height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>

</br> 

<br>

<p> Step 2. Naming your Resource Group and Setting the Deployment Region </p>
<p> > You can name your RG anything you'd like </p>
<p> > When setting the region of deployment, you could choose any region but you'd want to consider a few factors: i.e network connectivity, cost considerations, service availability, etc. </p>
<p> > Once you name RG and select the region of deployment, select *Review & Create* </p>
<p> > Your RG now goes through a validation phase. Once it passes validation, you may now select *Create* to create your RG.
<p align="center">
<img src="https://github.com/user-attachments/assets/d17fa066-b640-4a0e-bafd-52713e134f09" height="80%" width="80%" alt="Disk Sanitization Steps" />
<img src="https://github.com/user-attachments/assets/a96500ac-dc6d-4b47-8de2-b8a92db69dc8" height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>

</br>

<br>

<p> Step 3. Creating your Virtual Machine(s)</p>
<p> > Using Azure resource landing page, you could use the search box or select the shortcut to select Virtual Machines.</p>
<p> > Once on the Create a Virtual Machine landing page, be sure the subscription textbox is filled out with the appropriate subscription.</p>
<p> > In the Resource Group textbox, be sure to choose the RG that you created previously.</p>
<p> > For Virtual machine name: Choose it wisely. Try not to make it complicated.</p>
<p> > For the Region: Choose the same region as you did when setting up your RG.</p>
<p> > Selecting Image type: Choose the operating system based on your needs. In the sample photo, Windows 10 Pro, 
        version 22H2 was used. </p>
<p> > Selecting Size: This determines factors such as your vm's workload requirements like the central processing unit (CPU), memory (RAM), storage, network, etc. Depending on the selected size would determine pricing as well and you would want to make sure you're getting a good "bang for your buck".</p>
<img src="https://github.com/user-attachments/assets/e5c47e7f-ba79-441c-9264-7081f46935ab"/>
<img src="https://github.com/user-attachments/assets/8e60800d-65df-4498-ab3f-e2231578d2fb"/>
</p>

</br>

<br>

<p> Step 4. Creating User Name and Password for VM</p>
<p> > For the Authentication Type, you could either options presented whichever you feel is easiest. In the example photo, password was choosen.</p>
<p> > Create a username of your choice and password of your choice.</p>
<p> > Confirm your password choice in the third textbox.</p>
<p> NOTE* Be sure to keep track of your credentials.
<img src="https://github.com/user-attachments/assets/38320c00-3038-4bb7-9ac7-93193b0bef35"/>
</p>
</br>
<br>

<p> Step 5. Deploying Virtual Machine</p>
<p> > After creating your credentials for your vm's Administrator Account, select "Next: Disk>" and "Next: Networking>".</p>
<p> > On the Networking page it shows the name of your virtual network that will be auto-created along with the vm. Select "Review & Create".</p>
<p> > You'll then be directed to the Management page which shows your vm validation and pricing information. Once your vm passed its validation phase, select "Create".</p>
<p>
<img src="https://github.com/user-attachments/assets/db00919b-df92-4b62-a8a5-10439298b27a"/>
<img src="https://github.com/user-attachments/assets/2926780a-65ed-4259-a182-b50dbd69849c"/>
</p>
</br>
<br>

<p> Step 5. Deploying Virtual Machine</p>
<p> > After creating your credentials for your vm's Administrator Account, select "Next: Disk>" and "Next: Networking>".</p>
<p> > On the Networking page it shows the name of your virtual network that will be auto-created along with the vm. Select "Review & Create".</p>
<p> > You'll then be directed to the Management page which shows your vm validation and pricing information. Once your vm passed its validation phase, select "Create".</p>
<p>
<img src="https://github.com/user-attachments/assets/db00919b-df92-4b62-a8a5-10439298b27a"/>
<img src="https://github.com/user-attachments/assets/2926780a-65ed-4259-a182-b50dbd69849c"/>
</p>
