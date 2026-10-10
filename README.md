# My-Repository
The is my walkthrough on how to create a RHEL repository

<img width="897" height="141" alt="Login as root user" src="https://github.com/user-attachments/assets/3d77f12d-bb4c-4290-b558-a004bf73e531" />
First login as root user

<img width="898" height="49" alt="Create repo directory" src="https://github.com/user-attachments/assets/4ee6fab9-3c85-4eb4-beea-7a77d50660f1" />
Then create the repo directory


<img width="1284" height="473" alt="Use blkid to find the UUID for the iso" src="https://github.com/user-attachments/assets/3927396c-cbf5-4906-bbe1-ab62ae93397f" />
Now use the blkid command to find the UUID for the iso


<img width="1278" height="48" alt="Mount the UUID to fstab" src="https://github.com/user-attachments/assets/3559ce3b-1fc1-47a4-968f-7a16cb712807" />
<img width="1284" height="803" alt="Mount iso to repo directory in fstab" src="https://github.com/user-attachments/assets/0fee8bf8-d339-46ad-845b-f8ebb62ae085" />
After that mount the UUID to fstab



<img width="1279" height="50" alt="Mount with mount a" src="https://github.com/user-attachments/assets/224f0766-2c84-4a09-943e-62a16b20dbe5" />
Mount with the mount -a command


<img width="1281" height="53" alt="Make sure it persist after reboot with Systemctl daemon reload" src="https://github.com/user-attachments/assets/7210db64-6a4c-4d61-be30-2f4167ed897c" />
Make sure it persist after reboot with systemctl daemon-reload


<img width="1280" height="85" alt="mount persists" src="https://github.com/user-attachments/assets/6d8e78d0-ee7a-4dda-b617-2cc1217264df" />
See the mount persists after reboot 


<img width="1281" height="629" alt="add repo files BaseOS and AppStream" src="https://github.com/user-attachments/assets/5d25a812-8d09-49be-ad62-24a625498242" />
Now you add repo files BaseOS and AppStream 



<img width="1282" height="52" alt="Vi into repo" src="https://github.com/user-attachments/assets/9c8e407f-265a-4849-97ae-c2fff3cc2076" />
<img width="1283" height="800" alt="inside repo" src="https://github.com/user-attachments/assets/6e1ba6c1-047d-496d-8ec3-776de39b79ca" />
vi into repo


<img width="1281" height="803" alt="add gpgcheck to AppStream" src="https://github.com/user-attachments/assets/0383a9b1-6600-489b-a5c3-f5da4207ddc4" />
<img width="1281" height="806" alt="add gpgcheck to BaseOS" src="https://github.com/user-attachments/assets/b532883c-9804-41d2-9d68-e0b9b83e9ae8" />
Add gpgcheck to both AppStream and BaseOS config file


<img width="1279" height="397" alt="check repolist" src="https://github.com/user-attachments/assets/4169d624-cf03-4f41-95c2-0970ff31f1c8" />
Check repolist


<img width="1284" height="454" alt="Makecache to make sure the repo is functional" src="https://github.com/user-attachments/assets/d10a9600-bde4-4290-8afd-13ebef3b1350" />
Install makecache in dnf to make sure the repo is functional


<img width="1280" height="747" alt="install httpd package 1" src="https://github.com/user-attachments/assets/76b9ec99-8534-45b7-a24f-b3c575f32d0e" />
Install package

<img width="1280" height="804" alt="install httpd package 2" src="https://github.com/user-attachments/assets/798b7f6c-c38c-4132-bb2b-4c9754acb40b" />
<img width="1280" height="802" alt="install httpd package 3" src="https://github.com/user-attachments/assets/b37217a3-4d7e-40c1-9a28-85e9e4e8410c" />
<img width="1286" height="754" alt="install httpd package 4" src="https://github.com/user-attachments/assets/8a029822-4db7-4f0b-a731-18115119c7b6" />
Now you have created your RHEL repository

