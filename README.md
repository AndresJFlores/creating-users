<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- Power Shell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup remote desktop for non-administrative users on client PC
- Create a lot of additional users and attempt to log into client PC with one of the users


<h2>Deployment</h2>


<p>
logging into the domain PC as the administrator. <br /> <br />

![Screenshot 2025-03-17 155723](https://github.com/user-attachments/assets/0482ac5b-a929-4783-9849-864461ee1bfe)

</p>
<br />



<p>Here i have copied over a script into PowerShell ISE, ran the script, and generated over 500 users. <br /> <br />

![image](https://github.com/user-attachments/assets/9c942e09-6c24-40b6-ab05-9d69fe18edbe)


</p>
<br />


<p>
Observing the newly created accounts accounts in Active Directory. <br /> <br />

![Screenshot 2025-03-17 162238](https://github.com/user-attachments/assets/c1b8230e-ef04-4d05-9281-3e5c6d9b40ec)

</p>
<br />

<p>
Choosing an account to attempt login. <br /> <br />

![image](https://github.com/user-attachments/assets/937a8c69-b5a5-4b18-ae19-8b267147388b)

![image](https://github.com/user-attachments/assets/ec6dc585-2105-4179-b159-5b92ca942fc3)

![Screenshot 2025-03-17 165345](https://github.com/user-attachments/assets/c69d8a7e-1503-4a08-b440-4cc57f7a1006)

</p>

