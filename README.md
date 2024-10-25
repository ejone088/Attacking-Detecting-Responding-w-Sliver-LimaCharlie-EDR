# VM-Creation-EDR-Installation
Here I will be documenting the creation of 2 virtual machines (Ubuntu &amp; Windows) and installation of LimaCharlie for EDR purposes. The Ubuntu machine will later be used for attacking the Windows machine. I will want to keep track of the action from a learner's and SOC analyst's perspective, therefore, LimaCharlie will be installed on the Windows machine.

Source (Eric Capuano's Guide): https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-part

# Windows 11 Setup
Disabled Windows Security features and Microsoft Defender using Windows Registry for testing purposes

<img width="400" alt="image" src="https://github.com/user-attachments/assets/be1afba1-5a2f-40e0-b980-71e5acf349eb">

<img width="487" alt="image" src="https://github.com/user-attachments/assets/f8f2f75b-a34f-4e9d-a7f8-57a79f47cfac">

Downloading and installing Sysmon

<img width="479" alt="image" src="https://github.com/user-attachments/assets/d4bcd2dd-240f-4616-bb4b-93e5c44c4673">

Confirmed Sysmon is up and running then checked for logs

<img width="480" alt="image" src="https://github.com/user-attachments/assets/f93bd988-14c0-4e30-bb08-94ec372110f0">


Successfully installed a sensor (EDR agent) from LimaCharlie

<img width="477" alt="image" src="https://github.com/user-attachments/assets/82260ee0-9dd8-41bf-aa4f-1e99ef234461">

Created an Artifact Collection Rule that has LimaCharlie collecting Sysmon logs

<img width="447" alt="image" src="https://github.com/user-attachments/assets/a6530068-1f3e-4416-8464-43e96581ac25">

# Ubuntu Server Setup
Installed Silver for C2 functionality

<img width="599" alt="image" src="https://github.com/user-attachments/assets/5b203e95-9c62-44aa-8080-f2e07f623e5c">




