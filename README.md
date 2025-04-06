<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
</p>
<p>

 </p>
<p>   
<img src="https://github.com/user-attachments/assets/678eb6e0-9f65-4b2d-8b8b-49dce18ef174"

In order to use the osTickting software correctly I had to first create a Virtual Machine to run the software on.
- Here is where you go to create a new virtual machine.
</p>
<br />
  
</p>
<img src="https://github.com/user-attachments/assets/19a37a98-264a-4fdd-be46-35b62b10d1c7"

After you select create new virtual machine tab you will see this pop up.
- First you must get a subscription if you don't already have one, that will allow you to use the software.
- After you get the subscription you can then go ahead and selete the resource group you want to house the information for the program.
  

</p>
<br />
</p>
<br />
<img src="https://github.com/user-attachments/assets/78eb5a07-e11b-471f-9693-6bb71549f3a9"

Next you scroll down to where you see (Virtual Machine Name) and you input the one you want to use.
- Then you selete what region you want to use, for myself I choose to use US East US 2.
- Make sure you use the same region for all of your Virtual Machines.
  

  
</p>
<br />
<img src="https://github.com/user-attachments/assets/95cc715a-ebb1-4d0f-a158-cd5af6b11fe9"

 Continue to scroll down until you see the word Image, there you will select Windows 10 Pro for this assignment.
    

</p>
<br />
<img src="https://github.com/user-attachments/assets/82eb6261-1f04-4116-b301-ee35d367327b"

As you scroll down more you will see the word Size, there you will select an option with 2 vcpus and at least 8 GIBs of memory.
    
</p>
<br />
<img src="https://github.com/user-attachments/assets/5271ccd3-5611-40b9-90fd-9491c9af8b26"

As you continue to scroll you will select a username and password that you know you will remember and enter them.
    
</p>
<br />
<img src="https://github.com/user-attachments/assets/fb48c695-dfb1-471c-83b8-13c261f22c42"

At the end you will see something that says Licensing and you will make sure to check that box before going to the next step.
- Next you will see a button that says next:disk and you click on it.

<br />
</p>
<img src="https://github.com/user-attachments/assets/2fb94f44-ba23-403c-a4a6-9b233171458d"

On this page you do not have to select anything so you can click the next:networking button and continue.
    

</p>
<br />
<img src="https://github.com/user-attachments/assets/2d0621d5-1afa-40a3-97e5-fcd33e01fb9c"

Here where is says virtual network you will create a new one and name it, I chose to name mine osTicket-Vm
- Next you will see a button that says Review and Create and you should click that button.

</p>
<br />
<img src="https://github.com/user-attachments/assets/8f6871f9-945f-4ed2-96c2-55b040c44d29"

After the validation has passed you then select create, after which the system will start to add needed software to you Virtual Machine.

    
</p>
<img src="https://github.com/user-attachments/assets/3987d823-e439-4d0d-b817-5abf93afdc16"

Here you can see that the deployment is complete and you are ready to use your virtual machines.    

</p>
<br />
<img src="https://github.com/user-attachments/assets/fef62c2b-de09-4e3e-8427-111297ffd0e7"

Here you can see that the virtual machine is working and ready to use.
- You can see where the I highlighted the Public IP Address you will need to log on to the remoted desktop.

</p>
<br />
<img src="https://github.com/user-attachments/assets/7679708b-63b6-4a8c-87d0-565731cda7a6"

Here you can see where to paste the Public Ip Address needed to log in to the virtual machine.  

</p>
<br />
<img src="https://github.com/user-attachments/assets/2bef8145-6d74-4219-8d6e-fbb6ad99b573"

After you have logged in with the corrected IP Address are then able to select. If you do not see yours you can click the (use a different account) tab to log you credentials.

</p>
<br />
<img src="https://github.com/user-attachments/assets/747ca5d2-efc4-4474-bc1e-90367d7282ef"

Here you will use the Username and Password you chose earlier to login to the remote desktop.  

</p>
<br />
<img src="https://github.com/user-attachments/assets/e4f15331-1797-42a9-83f0-2a42d16b915b"

You may see a message about allowing the connection to continue and you just select yes.
- And that will be the end of the setup.

</p>
<br />

<p>

