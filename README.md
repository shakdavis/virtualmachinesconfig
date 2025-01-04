# virtualmachinesconfig

<p align="center">
<img src="https://github.com/user-attachments/assets/2b4e7618-3ee1-462e-a84f-a4bf83d7ae15" height="40%" width="80%" />
</p>
<br>
<h1> Resource Group & Virtual Machine - Configuration & Deployment </h1>

This step-by-step tutorial outlines the prerequisites, configuration, and deployment of a resource group and virtual machine using Microsoft Azure.
</br>

<br>
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

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

<p align="left"> Step 1. Create a Resource Group </p>
<p> > Once logged to Azure, the resource landing page. From here you will be able to locate the different services that Azure has to offer.</p>
<p> > You could either search for Resource Groups in the search engine at the top of the page or select the shortcut.</p>
<p> > Once on the Resource Group landing page, select "Create".</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/6d46ff79-29c5-4cfb-8b7a-ea801e5f0c77" height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>

</br> 

<br>

<p> Step 2. Naming Resource Group and Setting the Deployment Region</p>
<p> > You can name your RG anything you'd like.</p>
<p> > When setting the region of deployment, you could choose any region but you would want to consider a few factors: i.e network connectivity, cost considerations, service availability, etc.</p>
<p> > Once you name your RG and select the region of deployment, select *Review & Create*.</p>
<p> > The RG now goes through a validation phase. Once it passes validation, you may now select "Create" to create your RG.</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/d17fa066-b640-4a0e-bafd-52713e134f09" height="80%" width="80%" alt="Disk Sanitization Steps" />
<img src="https://github.com/user-attachments/assets/a96500ac-dc6d-4b47-8de2-b8a92db69dc8" height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>

</br>

<br>

<p> Step 3. Creating a Virtual Machine</p>
<p> > Using Azure's resource landing page, you could use the search box or select the shortcut to select Virtual Machines.</p>
<p> > Once on the "Create a Virtual Machine" landing page, be sure the subscription textbox is filled out with the appropriate subscription.</p>
<p> > In the Resource Group textbox, choose the RG that you created prior to step 3.</p>
<p> > For Virtual machine name: Choose it wisely. Try to avoid anything complicated.</p>
<p> > For the Region: Choose the same region as you did when setting up your RG.</p>
<p> > Selecting Image type: Choose the operating system based on your needs. In the sample photo, Windows 10 Pro,version 22H2 was used.</p>
<p> > Selecting Size: This determines factors such as your vm's workload requirements like the central processing unit (CPU), memory (RAM), storage, network, etc. Depending on the selected size would determine pricing also.</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/e5c47e7f-ba79-441c-9264-7081f46935ab"/>
<img src="https://github.com/user-attachments/assets/8e60800d-65df-4498-ab3f-e2231578d2fb"/>
</p>

</br>

<br>

<p> Step 4. Creating User Name and Password for VM</p>
<p> > For the Authentication Type, you could select either option presented, whichever you feel is easiest. In the example photo, "password" was choosen.</p>
<p> > Create a username and password of your choice.</p>
<p> > Confirm your password choice in the third textbox.</p>
<p> NOTE* Be sure to keep track of your credentials.</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/38320c00-3038-4bb7-9ac7-93193b0bef35"/></p>
</br>

<br>

<p> Step 5. Deploying your Virtual Machine</p>
<p> > After creating your credentials for your vm's Administrator Account, select "Next: Disk>" and "Next: Networking>".</p>
<p> > On the Networking page, it shows the name of the virtual network that will be auto-created along with the vm. Select "Review & Create".</p>
<p> > You'll then be directed to the Management page which shows your vm validation and pricing information. Once the vm has passed the validation phase, select "Create".</p>
<p> After a few mintues, your virtual machine deployment should be complete.</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/db00919b-df92-4b62-a8a5-10439298b27a"/>
<img src="https://github.com/user-attachments/assets/2926780a-65ed-4259-a182-b50dbd69849c"/>
<img src="https://github.com/user-attachments/assets/b62a1d32-274b-477f-8c8e-04c6b24f93ef"/>
</p>
</br>
<br>

<p> Step 6. Resource Group Review</p>
<p> > If you return to your Resource Group, you will notice other resources were created within the resource group; i.e. virtual machine, virtual network, network security group, etc.</p>
<p> > All resources should be deployed in the same location, i.e. Canada East.</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/60b035ec-d1f5-40e3-9eca-7f279089f8a7"/>
</p>
</br>

<p align="center"> Congratulations! You have successfully configured and deployed a virtual machine using Microsoft Azure!</p>
