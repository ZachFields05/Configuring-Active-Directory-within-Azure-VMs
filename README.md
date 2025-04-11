<img width="713" alt="image" src="https://github.com/user-attachments/assets/ea6fdd2e-9852-42af-9d10-58320ff317e7" />


# Configuring-Active-Directory-within-Azure-VMs

1:Create a Resource Group

2:Create a Virtual Network and Subnet

3:Create the Domain Controller VM (Windows Server 2022) named “DC-1”

4:Setup Client-1 in Azure
—
Create the Client VM (Windows 10) named “Client-1”

<img width="788" alt="image" src="https://github.com/user-attachments/assets/1c82c4f9-d781-48f4-98f2-2d8922689ca4" />

1:After VM is created, set Client-1’s DNS settings to DC-1’s Private IP address
2:After VM is created, set Domain Controller’s NIC Private IP address to be static


<img width="439" alt="image" src="https://github.com/user-attachments/assets/a6b9e214-4c6c-4798-96a7-d4daa76c95c1" />


INSTALL ACTIVE DIRECTORY


<img width="725" alt="image" src="https://github.com/user-attachments/assets/721bf0b8-6dcd-41ed-b565-cbb559e51bc1" />

CREATE USER AND ORGANIZATIONAL GROUPS




<img width="635" alt="image" src="https://github.com/user-attachments/assets/78a7a350-2ad2-4fce-a635-c8a13e602fbe" />

ADD "COMPUTERS" TO THE DOMAIN

<img width="547" alt="image" src="https://github.com/user-attachments/assets/3021089b-9e7c-4bcf-b215-7400eab0b670" />


ADD USERES USING POWERSHELL AD


<img width="674" alt="image" src="https://github.com/user-attachments/assets/00047258-84d6-4926-89b8-fbcc716a3ee8" />
