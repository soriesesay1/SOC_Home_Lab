# SOC_Home_Lab
Building A SOC Home Lab

Pfsense Installation into VirtualBox:

We go New at the top right:

![image](https://github.com/user-attachments/assets/7db8bb92-b664-456e-bc5e-ea5985c0060a)

In the type section, I choose BSD because Pfsense is an open-source firewall platform. For the Hardware, I choose 4gb to make Pfsense faster and since I have so many space and processor 3 CPUs.

![image](https://github.com/user-attachments/assets/5fc56806-76a7-45c8-bf02-ee317b2a2471)

To configure the Network of our SOC Home Lab, we go to Settings at the top right and scroll down to Network. For the SOC Lab to work, we need 3 networking Adapters. The first adapter is NAT which is the default network to VirtualBox, second is Internal Network which is the network created by VB.

![image](https://github.com/user-attachments/assets/8eedfe47-47cd-4550-bf47-3efe00b6f153)

![image](https://github.com/user-attachments/assets/ade6d558-5ee4-48b0-b6ea-03931ee5513e)

![image](https://github.com/user-attachments/assets/3433138e-852c-4503-b566-e78169cf0673)

Power On Pfsense and Installation:

![image](https://github.com/user-attachments/assets/e4249f25-a654-4d97-a0af-890b25bc7ef4)

![image](https://github.com/user-attachments/assets/af6a2e6f-2ebb-423f-876d-87997e2e42cb)

![image](https://github.com/user-attachments/assets/cc36c60a-595a-4dde-91de-7e825b8568c7)

![image](https://github.com/user-attachments/assets/95ff3f93-3b1b-4e8b-84be-2c05f28a15b7)

![image](https://github.com/user-attachments/assets/c11879cb-d298-4ef5-b944-1489274746e9)

![image](https://github.com/user-attachments/assets/24a9b74a-5f84-41c5-8bb3-d240a0dc0164)

![image](https://github.com/user-attachments/assets/6cf9ec60-d6be-4807-a3f4-e67ec6b58b3d)

![image](https://github.com/user-attachments/assets/8b483f6e-9527-40f6-adc0-8aeb0b911ba9)

![image](https://github.com/user-attachments/assets/5839db60-a363-450b-a675-92f9030c863d)

![image](https://github.com/user-attachments/assets/e5eb30de-9b84-4280-8653-630b8b2b98c2)

![image](https://github.com/user-attachments/assets/aad26b45-9783-456e-b28f-37827cdc966d)

![image](https://github.com/user-attachments/assets/dae515bb-ecc6-4340-bfed-1d0b7decbff7)

![image](https://github.com/user-attachments/assets/502dcec9-8070-4877-ac68-b06efedf2ddc)

![image](https://github.com/user-attachments/assets/cc44b084-27e8-48d5-b1e5-3d51bb24bb4c)

Another thing to consider before rebooting Pfsense is to unmount it by going to Devices at the top right, hover Optical Drives, and click on the Pfsense installer to unmount it.

![image](https://github.com/user-attachments/assets/db233eb5-f734-4f15-b5c0-7abf06d9540e)

Click Force Unmount and reboot the Pfsense iso. Below shows we have successfully installed Pfsense.

![image](https://github.com/user-attachments/assets/6c49ae3d-af62-4c0c-9774-f7a58688d7db)

Configuration and Assign Interface:

Press 1 to Assign Interface:

![image](https://github.com/user-attachments/assets/692a5af6-316f-4640-8990-eeb77f894231)

Assigned Interface:

![image](https://github.com/user-attachments/assets/653a905c-6ad7-45ab-9982-918467513ca0)

Interface Set:

![image](https://github.com/user-attachments/assets/a31cca0a-0de8-47f5-a93e-169100dbd70c)

IP Configuration:

I assigned a new IP Address to the LAN Interface

![image](https://github.com/user-attachments/assets/12a8ab72-7d0c-4ce1-a209-8ec18ab2ee2c)

Pfsense Configuration Done!

![image](https://github.com/user-attachments/assets/cb1cfcc6-20ba-4b77-83c2-7f2a0e7d6167)


Active Directory Installation:

Install Active directory Windows Server 2022

To download to https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022 and select Download the ISO which will take you to the download page and input your details below. https://info.microsoft.com/ww-landing-windows-server-2022.html

![image](https://github.com/user-attachments/assets/fb04bb03-0a95-49f5-87a2-85690a5ff296)

Active Directory Windows Server 22 VirtualBox Installation:

![image](https://github.com/user-attachments/assets/c27cf23d-34b5-4a0d-84c6-056f9cd483f8)

Hardware:

![image](https://github.com/user-attachments/assets/248469c9-a08b-4fa2-8465-ce56a53f8131)

Network:

![image](https://github.com/user-attachments/assets/bc046a5b-cc83-4079-a35a-ce12dc805eb7)

Power On Windows Server 22 and installation:

![image](https://github.com/user-attachments/assets/b5a9176c-04ac-4bb9-bb7b-4ab931ae6b12)

Click Next:

![image](https://github.com/user-attachments/assets/c8a3501e-83da-4e22-8d45-3ecc836d74a6)

Click on Custom:

![image](https://github.com/user-attachments/assets/3b726750-d0b6-4755-b4a2-142211ade3bd)
![image](https://github.com/user-attachments/assets/fc2543b0-eb10-406f-ab85-da320cd5a307)
![image](https://github.com/user-attachments/assets/34c2630e-8ee4-447d-8252-223ffdee8879)

Installation Complete:

















