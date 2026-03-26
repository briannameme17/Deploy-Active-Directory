# Deploying Active Directory in Microsoft Azure  

## Overview  
This project demonstrates how to deploy and configure Active Directory Domain Services (AD DS) in Microsoft Azure using a Domain Controller (DC-1) and a client machine (Client-1). The process includes installing AD DS, creating a domain, managing users and permissions, and joining a client machine to the domain. This setup reflects real world IT responsibilities such as user management, access control, and maintaining secure network environments.  

---

## Steps Taken  

1. Logged into DC-1 and installed Active Directory Domain Services (AD DS) using the Add Roles and Features Wizard  

2. Promoted the server to a Domain Controller by creating a new forest (mydomain.com) and completed the configuration  

3. Restarted the server and logged back in using domain credentials (mydomain.com\labuser)  

4. Opened Active Directory Users and Computers (ADUC) and created Organizational Units named **_EMPLOYEES** and **_ADMINS**  

5. Created a new Domain Admin user (Jane Doe) with the username **jane_admin** and added the account to the Domain Admins group  

6. Logged out and reconnected to DC-1 using Remote Desktop as **mydomain.com\jane_admin** to continue administrative tasks  

7. Joined Client-1 to the domain (mydomain.com), restarted the machine, and verified it appeared in Active Directory  

8. Created a new OU for clients and organized resources by placing Client-1 into the appropriate OU and confirming proper domain connectivity  

---

<p align="center">

<img src="Images/Roles-1.png" width="600">  
<img src="Images/Roles-2.png" width="600">  
<img src="Images/install.png" width="600">  
<img src="Images/OU.png" width="600">  
<img src="Images/New user.png" width="600">  
<img src="Images/Admin.png" width="600">
</p>
