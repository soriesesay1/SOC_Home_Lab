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
![image](https://github.com/user-attachments/assets/86c796bf-e889-4bbb-9a67-f60111cfa763)

Windows Server 22 Installation Complete:
![image](https://github.com/user-attachments/assets/8e4a3699-3b99-4007-80cf-71d4ce055179)

Configuration of Windows:
Go to "Open Network & Internet Settings."
![image](https://github.com/user-attachments/assets/08174e1d-79c6-413f-a9df-75bd41c84b66)

Change adapter options.

Select your card properties.

Go to "Internet Protocol Version 4" > Properties.

Assign IP.

Try to join the gateway. (so, your LAN INTERFACE in Pfsense)

Rename the server with an easy name to remember/use.
![image](https://github.com/user-attachments/assets/346856da-85c8-424d-84dc-dc75a557823a)

Rename PC:
![image](https://github.com/user-attachments/assets/d7f215e1-fb74-497f-a6f8-08c23d809675)

After rebooting your AD Server, make sure the Pfsense Network Firewall is ON so the AD can connect.
![image](https://github.com/user-attachments/assets/6f076170-52ac-48e8-b821-82bc8e050acf)

Installation of Active Directory:

Click "Add roles and features."
![image](https://github.com/user-attachments/assets/b2936de8-8180-4ecd-8581-6e133f3cdcee)

Add a role-based installation.

Add "Active Directory Domain Services."
![image](https://github.com/user-attachments/assets/53a2f407-5539-418d-8037-91a7d9f62108)

Active Directory Installation Complete:
![image](https://github.com/user-attachments/assets/e06e7573-3c6e-473d-b1ba-626fa0a10231)

Leave the other Windows settings with defaults configurations. After it is complete, promote this server to a domain controller.
![image](https://github.com/user-attachments/assets/811629f7-1de5-42d9-adeb-b25acc518ce1)

Add a new Active Directory Forest.
![image](https://github.com/user-attachments/assets/f336748e-fe7c-4603-853f-5faa5c08098d)

Leave default configurations and give a password.
![image](https://github.com/user-attachments/assets/ec25cf9f-a2cc-4341-a7e1-eede3629d77c)

Leave DNS part by default.

Check the NetBIOS domain name. 

Leave the default path.

Launch the install.

Reboot when asked for it.
![image](https://github.com/user-attachments/assets/e96fcf71-c0c4-4b40-b7fe-e542fc62ab16)
![image](https://github.com/user-attachments/assets/9244752f-965e-4d59-a37b-beadb6ffe676)
![image](https://github.com/user-attachments/assets/0f974433-637f-4cbb-8c30-e6184f426f01)

Everything Looks Good in Our Soc Active Directory Server.
![image](https://github.com/user-attachments/assets/d1aa2fd2-6424-4796-a283-cba7d78e3725)

Configuration of Active Directory:

Now you have the Active Directory Server, you need to populate it with misconfiguration to perform analysis. We will use BadBlood for this task, please follow the instructions below:

•	Download it on the AD

•	Extract it

•	Launch Powershell as administrator

•	Go to Badblood folder

•	Launch Invoke-BadBlood.ps1

•	Let the magic happen (this can take several minutes)

To get BadBlood, I used the following commands and powershell should be open admin:

•	cd Downloads

•	ls

•	cd BadBlood-master

•	ls

•	.\Invoke-BadBlood.ps1

![image](https://github.com/user-attachments/assets/480b87a4-915c-4821-a82b-a6220a5a8b74)
For some reason the execution didn’t go through.


Windows Workstation:

Go to Microsoft.com if you did not have the MediaCreationTool_22H2 and download it. Follow Below:

•	Launch it.

•	Accept the software license.

•	Select "create an installation support" to make an ISO.

•	Select the English language.

It should look like this below if you did not have the MediaCreationTool_22H2
![image](https://github.com/user-attachments/assets/663fe3ff-f7e9-4769-9def-6285f33f2a67)

Hardware:
I gave mine 8gb and 4CPUs because of the space and I don’t wat it to be slower. 
![image](https://github.com/user-attachments/assets/6e6a912f-960c-4872-a4e6-4e2eebdb23e8)

Network:
![image](https://github.com/user-attachments/assets/ac12b334-5956-443b-9f34-a2f15f0c5800)

Launch the VM: It will ask you which ISO VirtualBox must mount on the VM, load the Windows Server one.

Installation of Windows:
![image](https://github.com/user-attachments/assets/41a840a4-c8b3-4284-9e95-ec507b63e987)

Click "Install Now".

Click "I don't have a product key". (or enter the one you have)
![image](https://github.com/user-attachments/assets/c27842df-c22b-47dc-983d-cb4a7450e853)

![image](https://github.com/user-attachments/assets/3dda6262-25fe-4e44-926b-18695dd6b716)
![image](https://github.com/user-attachments/assets/43d9fcb3-c042-4b3e-96a3-f3e9373ee7cc)

Accept the license terms and click Custom Install.
![image](https://github.com/user-attachments/assets/29621598-2a9d-478f-8418-e4d4b51374e1)

Click on the only drive you have and select "Next".
![image](https://github.com/user-attachments/assets/a61b44a8-757b-48ff-ab16-f3aa18d6f7bd)

When the Installation is complete, we click reboot. 

After reboot, follow the default steps. When you get to “Lets connect you to a network” Click on “I don't have internet" in the left bottom corner.

Click "Continue with limited setup" in the left bottom corner.
![image](https://github.com/user-attachments/assets/81787a29-a935-4572-bc8e-141625e52e2a)

•	Name your local account and secure it with a password.

•	Setup your 3 security questions.

•	Set all other options to the minimal value. (no location, no track, etc.)

![image](https://github.com/user-attachments/assets/4473e4a7-561e-4700-bb73-e7fee5cfeeb1)


Configuration of Windows:

•	-Connect to your administrator account.

•	Go to "Open Network & Internet Settings"

•	Change the adapter options.

•	Select your card properties.

•	Go to "Internet Protocol Version 4" > Properties.
![image](https://github.com/user-attachments/assets/750206c4-d927-4d3f-b7b1-5519e567ee10)

I have internet access after the configuration.

Rename the Windows PC:
![image](https://github.com/user-attachments/assets/dadb8239-2a11-4164-85fb-3e507725bb8f)


We Add the Workstation to a Domain:

To Do that, first right-click on the Windows Icon at the bottom left and click Systems. Under Related Settings, click Advanced System Settings and select Computer Name at the top left.
![image](https://github.com/user-attachments/assets/4e83d3c4-1ad4-4db7-81ec-b7e313569595)

Below Computer Name, click Change under Network ID. In the Computer Name/Domain changes, under Member of, select Domain and type in SOC and click OK.
![image](https://github.com/user-attachments/assets/3107bb38-cef4-4fae-b95d-af1e089f5156)

After Hours of trying to join my Client Machine to my Domain in my Active Directory, I finally succeeded. If you are trying to join your Client Machine to your AD, use the AD login like this below.
![image](https://github.com/user-attachments/assets/ce605233-cb24-4f73-a2c2-673658f0af34)

Whichever Name you used here is the same one you should use to join the Domain and password. Success!!
![image](https://github.com/user-attachments/assets/362161a7-7f8a-48ea-8265-8e4433ac7cdc)
Restart the Client Machine!!


To verify that we have successfully join the Client Machine to our Domain in Active Directory, right-click on the Windows Icon, and select System, go to Advanced Settings, Computer name, select Change, and you will see the Domain is Active in our Windows Client machine.
![image](https://github.com/user-attachments/assets/53e7e2d4-5b35-412b-bf6f-27159cfbb0ed)

Sysmon: - We have Downloaded Sysmon from Windows Sysinternals page and Extract it. 
![image](https://github.com/user-attachments/assets/234c940d-fb4c-4542-b09a-26a7858838b3)

We Downloaded the XML Configuration File and save it to the Sysmon file. 
![image](https://github.com/user-attachments/assets/f40a1ce7-42e2-4853-9778-db9d627801c1)


Install Sysmon in Powershell:

We open Powershell as an Administrator, I run the following commands below:
![image](https://github.com/user-attachments/assets/3c716d4e-a44c-4d31-85a4-2adb37a16105)
![image](https://github.com/user-attachments/assets/1b474625-5959-46df-96a2-75d88071ae83)


CrowdSec Installation On Our Client Machine:

Account

•	Go to the CrowdSec site https://www.crowdsec.net/

•	Click Login and Select "create free account or signup".

•	Create the free account and log in to CrowdSec.

•	Access to Login
![image](https://github.com/user-attachments/assets/7af21998-b472-4423-aac6-ccda9c38a7af)
![image](https://github.com/user-attachments/assets/14af96c8-8d0a-4f0f-80ca-341b89104873)

Install CrowdSec Windows:

•	Go to the GitHub page https://github.com/crowdsecurity/crowdsec/releases/tag/v1.6.4

•	Download the .msi file on the Windows computer. (server and workstation)

•	Launch it.

After Download, Installation Next on both Server and Client Machine:
![image](https://github.com/user-attachments/assets/164de639-d883-4d88-802f-cb0f093e08bf)
![image](https://github.com/user-attachments/assets/d683f19a-dffe-4ed6-8574-1b9d4f384798)
![image](https://github.com/user-attachments/assets/fa1bb2f0-d2c0-42d0-93a5-2a5aa9507723)

After Installation of CrowdSec, we should the CrowdSec Folder and Lunch a Powershell directly from there.

To Do, So We Go To:

•	This PC

•	Program Files

•	CrowdSec
![image](https://github.com/user-attachments/assets/d7d0c750-506e-45e5-ac72-a747b6e22cbe)

After successfully enroll our Client-Machine to CrowdSec, I put the machine on a 2days watch to see if a breaking attempt will be conducted on our Machine and it did. We have 47 Scenarios by bad guys over the internet trying to exploit our Client-Machine. Majority of the attempts where CVE-2019, 22, apache_log4j2, and backdoor attempts. 
![image](https://github.com/user-attachments/assets/29f34616-66e9-4bcc-a05b-cb8474759732)
![image](https://github.com/user-attachments/assets/2f3f34d8-bcd3-4c2c-a36f-1ccbd654771c)
![image](https://github.com/user-attachments/assets/3c180b50-0596-4ce1-84ae-1c32bcbe5ea2)
![image](https://github.com/user-attachments/assets/25658454-56a3-4dc4-b297-aef3663c6dc3)


Investigation:

I try doing some investigation and I get to find out that the exploitation apache_log4j2_cve-2021-44228 was a Remote Code Execution Vulnerability (RCE) also known as Log4Shell. 

NIST:
![image](https://github.com/user-attachments/assets/b18fe694-2927-422c-9f94-256474b9cd6e)
![image](https://github.com/user-attachments/assets/eee7e63f-f52a-49b0-ab53-3e45475dea5a)

I tried another investigation CVE-2017-9841 which specifically targets PHP frameworks.
![image](https://github.com/user-attachments/assets/1eb7c46b-70ea-4a94-9ac0-66387fcefe0d)

More Details from NIST:
![image](https://github.com/user-attachments/assets/790f5cc8-f6c6-483f-9ea1-808a3fcc9906)
![image](https://github.com/user-attachments/assets/09640f32-082a-4719-b869-f4af16e60360)


CrowdSec does not offer automatic configuration during installation, in contrast to Linux. We will need to modify our acquisition configuration if you wish to be able to detect something other than RDP or SMB brute force, and that’s what we did. 

To Do That:

•	We Launch Powershell as an administrator in CrowdSec's folder C:\Program Files\CrowdSec

•	Paste in this command: .\cscli collections install crowdsecurity/windows-firewall
![image](https://github.com/user-attachments/assets/3a34dd9a-bf26-4cef-bdc2-fd8424c7b475)

After installing the acquis.yaml file in "C:\ProgramData\CrowdSec\config". I tried to install the Windows Firewall Bouncer which can be downloaded on github: https://github.com/crowdsecurity/cs-windows-firewall-bouncer/releases.
![image](https://github.com/user-attachments/assets/c9bfb36c-5d93-4809-925d-85b01a7fb066)

I reboot the Client-Machine after Windows Firewall Bouncer.

![image](https://github.com/user-attachments/assets/2fe1e5dc-57da-4969-a0ff-e496696f5ee8)
![image](https://github.com/user-attachments/assets/e1767968-cc00-4969-aebe-1f76fe012fd3)
![image](https://github.com/user-attachments/assets/eca318a5-04d0-4a2b-8b70-5c7af8e5c319)

End of My_SOC_Home_LAB!!

























