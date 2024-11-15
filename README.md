# EX-01 VIRTUAL MACHINE CREATION IN LINUX
## AIM
To install a Linux virtual machine (VM) using CentOS on VirtualBox or VMware Workstation.

## PROBLEM STATEMENT
This experiment involves setting up a virtual machine with CentOS, a popular Linux distribution. This setup allows users to practice Linux commands, test applications, and develop software in a virtualized environment without affecting the host system.

## ALGORITHM
Step 1:
Open VirtualBox or VMware Workstation

Step 2:
Go to File -> New to create a new virtual machine.

Step 3:
Enter a name for your CentOS VM.Choose Linux as the type and CentOS as the version (or select the closest option available if CentOS is not listed).

Step 4:
Select the CentOS ISO image you downloaded.
Set the base memory to 1024 MB (1 GB)
Allocate 1 processor core
Set the disk size to at least 20 GB
Complete the configuration by clicking Finish to create the virtual machine

Step 5:
Select the created VM, go to Details (or Settings), and navigate to the Network tab.
Configure Adapter 1 as NAT (for internet access through the host).
Configure Adapter 2 as Bridged Adapter (for direct access to the local network, if needed).
Click OK to save network settings.

Step 6:
Click Start to boot up the newly created virtual machine.
During installation, set a password for the root user.
After logging in to CentOS, open a terminal to start using the command line.

## COMMANDS
1. Switch to User: su username
2. View IP Address: ip a
3. Create a Directory: mkdir cloud
4. Change to the New Directory: cd cloud
5. Edit the Hostname File: vi /etc/hostname
6. View the Content of the Hostname File: cat /etc/hostname

## OUTPUT
### REG NUMBER: 212222240066
### NAME:MIDHUN AZHAHU RAJA P

![Screenshot 2024-11-15 115128](https://github.com/user-attachments/assets/84046dc3-3d42-4181-8bf5-dca72c749b66)

![Screenshot 2024-11-15 115226](https://github.com/user-attachments/assets/5bcef614-d58f-4d4e-956e-37fbf83febb6)


## RESULT
Thus, The installation of CentOS on a virtual machine using VirtualBox or VMware, providing a fully functional CentOS environment for testing and development is successfully executed.
 

  


