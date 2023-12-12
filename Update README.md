<h1>VirtualBox Virtual Machine Setup</h1>


<h2>Description</h2>
In this project, the user successfully established a virtual environment using VirtualBox, creating and configuring a virtual machine with precision. The step-by-step process included downloading and installing VirtualBox, setting up a virtual hard disk, mounting an operating system ISO, and installing the chosen operating system, culminating in a fully operational and seamlessly integrated virtual machine.
<br />


<h2>Languages Used</h2>

- <b>n/a</b> 


<h2>Environments Used </h2>

- <b>Oracle VM VirtualBox</b> (x86)
  

<h2>Project walk-through:</h2>

<p align="left">
Download and Install VirtualBox:

Go to the VirtualBox Downloads page.
Download the installer for your operating system (Windows, macOS, Linux).
Run the installer and follow the on-screen instructions to install VirtualBox. <br/>
<img src="https://imgur.com/8ZxjFG2.png" height="80%" width="80%" alt="VirtualBox"/>
<br />
<br />

Download an Operating System ISO:

Obtain an ISO file of the operating system you want to install on the virtual machine. This could be a Linux distribution, Windows, or another OS.:  <br/>
<img src="https://imgur.com/s2nblqH.png" height="80%" width="80%" alt="VirtualBox"/>
<br />
<br />

Open VirtualBox and Create a New Virtual Machine:

Open VirtualBox.
Click on "New" to create a new virtual machine.
Enter a name for your virtual machine, choose the type (e.g., Linux), and version (e.g., Ubuntu) based on the OS you're installing.
Click "Next.": <br/>
<img src="https://imgur.com/nw8AcnS.png" height="80%" width="80%" alt="VirtualBox"/>
<br />
<br />
Allocate Memory (RAM):

Choose the amount of RAM to allocate to the virtual machine. Ensure it doesn't exceed the recommended values for your host system.
Click "Next.":  <br/>
<img src="https://imgur.com/OH60dCN.png" height="80%" width="80%" alt="VirtualBox"/>
<br />
<br />
Create a Virtual Hard Disk:

Select "Create a virtual hard disk now" and click "Create."
Choose the hard disk file type (usually VDI) and click "Next."
Choose between a dynamically allocated or fixed-size hard disk. Dynamic allocation allows the virtual hard disk to grow as needed.
Set the size of the hard disk and click "Create.":  <br/>
<img src="https://imgur.com/gwGbUf9.png" height="80%" width="80%" alt="VirtualBox"/>
<br />
<br />
Mount the Operating System ISO:

With the virtual machine selected, click "Settings."
Under "Storage," select the empty disk under "Controller: IDE" and click on the disk icon next to "Optical Drive."
Choose a disk file and select the operating system ISO you downloaded.
Click "OK" to close the settings. <br/>
<img src="https://imgur.com/GpUb5kd.png" height="80%" width="80%" alt="VirtualBox"/>
<br />
<br />
Start the Virtual Machine:

With the virtual machine selected, click "Start."
The system will boot from the ISO file, and you can proceed with the installation of the operating system.:  <br/>
<img src="https://imgur.com/izPwC3k.png" height="80%" width="80%" alt="VirtualBox"/>

Complete the Installation:

After the installation is complete, remove the ISO from the virtual machine.
Restart the virtual machine. <br/>
<img src="https://imgur.com/GpUb5kd.png" height="80%" width="80%" alt="VirtualBox"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
