<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)


<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/Cb2Z2ux.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 1</b> - Created osTicket VM.
<p>
<br />

<p>
<img src="https://imgur.com/ZB97IXF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 2</b> - Connecting To VM Using RDP.
<p>
<br />

<p>
<img src="https://imgur.com/MlXMEy2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 3</b> - Installiing osTicket Zip Files.
</p>
<br />

<p>
<img src="https://imgur.com/otL6nMX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 4</b> - Configuring Virtual Machine For Client PC.
</p>
<br />

<p>
<img src="https://imgur.com/g5E9xza.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 5</b> - Domain Controller & Client VMs Created.
</p>
<br />

<p>
<img src="https://imgur.com/L9KaLmu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 6</b> - Changing DC-1 VM IP to Static.
</p>
<br />

<p>
<img src="https://imgur.com/QoYFd4z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 7</b> - Connecting to DC-1 Virtual Machine With RDP Using Public IP.
</p>
<br />

<p>
<img src="https://imgur.com/y7ybZli.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 8</b> - Turned Off Firewall State For Domain, Private, and Public Profiles.
</p>
<br />

<p>
<img src="https://imgur.com/qvAtDsN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 9</b> - Configuring DNS Server of Client To DC-1 Private IP Address.
</p>
<br />

<p>
<img src="https://imgur.com/Zyr9ftA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 10</b> - Connecting Client-1 VM With RDP Using Public IP.
</p>
<br />

<p>
<img src="https://imgur.com/EiFGGdI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 11</b> - Logged in As Client-1.
</p>
<br />

<p> 
<img src="https://imgur.com/q29pKRp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 12</b> - Ping From Client-1 to 10.0.0.4 Is Successful.
<p>
<br />

<p>
<img src="https://imgur.com/Qd5ZbWr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 13</b> - ipconfig Command Shows DNS IP 10.0.0.4.
<p>
<br />

<p>
<img src="https://imgur.com/ORnpexG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 14</b> - Installing Active Directory Domain Services To DC-1.
</p>
<br />

<p>
<img src="https://imgur.com/lrOxdLU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 15</b> - Installation of Domain Services Completed.
</p>
<br />

<p>
<img src="https://imgur.com/LHhO5Bt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>**STEP 16**</b> - Configuration & Installation of Domain Controller Success.
</p>
<br />

<p>
<img src="https://imgur.com/Q2ykguL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 17</b> - Initiating RDP Connection With CD-1 Under The New Domain Credentials.
</p>
<br />


<p>
<img src="https://imgur.com/nTlXc78.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 18</b> - Creating Organizational Unit Called _EMPLOYEES.
</p>
<br />

<p>
<img src="https://imgur.com/fJHKJZz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 19</b> - Creating Organizational Unit Called _ADMINS.
</p>
<br />

<p>
<img src="https://imgur.com/W2XO69v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 20</b> - Creating a New User In _ADMINS.
</p>
<br />

<p>
<img src="https://imgur.com/WLwBqaz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 21</b> - Adding Jane Doe As Member Of Domain Admins.
</p>
<br />

<p> 
<img src=https://imgur.com/4FnttOf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 22</b> - Logging Into DC-1 As jane_admin.
<p>
<br />

<p>
<img src="https://imgur.com/0mzLzBV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 23</b> - Confirmed That jane_admin as The Active Account.
<p>
<br />

<p>
<img src="https://imgur.com/7rTs2rD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 24</b> - Connecting Client-1 To Domain Controller.
</p>
<br />

<p>
<img src="https://imgur.com/TuVN2BZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 25</b> - Using Admin Account To Log In.
</p>
<br />

<p>
<img src="https://imgur.com/9Xl4WKB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 26</b> - Connection Successful.
</p>
<br />

<p>
<img src="https://imgur.com/DYnenmS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 27</b> - Confirmed That Client 1 Shows Up In The Domain Services.
</p>
<br />

<p>
<img src="https://imgur.com/zAWsw3W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 28</b> - Loggin Into Client-1 as jane_admin.
<p>
<br />

<p>
<img src="https://imgur.com/MljY0oU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 29</b> - Allowing Domain Users To Log Into Client-1.
<p>
<br />

<p>
<img src="https://imgur.com/yBLCQcZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 30</b> - Opening Up Powershell ISE as Administrator.
</p>
<br />

<p>
<img src="https://imgur.com/CRNiVFq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 31</b> - Making a create-users Folder For Script.
</p>
<br />

<p>
<img src="https://imgur.com/TcNt7BV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 32</b> - Running Powershell Script To Generate 1,000 Employees.
</p>
<br />

<p>
<img src="https://imgur.com/rzQwELO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 33</b> - Users Are Being Generated Under _EMPLOYEES.
</p>
<br />

<p>
<img src="https://imgur.com/R9NAjQz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 34</b> - Choosing Random Employee Account To Log Into Client 1 With.
</p>
<br />

<p>
<img src="https://imgur.com/pcz0mTm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 35</b> - Puporsefully Signing In With Wrong Password So Account Can Lock Out.
</p>
<br />

<p>
<img src="https://imgur.com/oeukSqk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 36</b> - Setting Lockout Duration For 30 Mins in DC-1.
</p>
<br />

<p>
<img src="https://imgur.com/dcRygSt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 37</b> - Setting Lockout Threshold To 5 Invalid Attempts.
</p>
<br />

<p>
<img src="https://imgur.com/jdjaBVN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 38</b> - Updating New Lockout Policy On civ.cenon User Account.
</p>
<br />

<p> 
<img src="https://imgur.com/C5N5cdE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 39</b> - Been Locked Out After Too Many Password Attempts.
<p>
<br />

<p>
<img src="https://imgur.com/Nib0T1D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<b>STEP 40</b> - Unlocked civ.venon Account in Active Directory.
<p>
<br />

<p>
<img src="https://imgur.com/lBHfpQK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 41</b> - Logged Back Into civ.venon Account.
</p>
<br />

<p>
<img src="https://imgur.com/e5uOVuZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 42</b> - Disabling cesi.feh Account.
</p>
<br />

<p>
<img src="https://imgur.com/WxNMLhx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 43</b> - Attempting To Login But Receive An Error Message.
</p>
<br />

<p>
<img src="https://imgur.com/S5fdtOX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 44</b> - Re-enabling cesi.feh Account.
</p>
<br />


<p>
<img src="https://imgur.com/tcTZLbt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 45</b> - Able To Login Into Account Now.
</p>
<br />

<p>
<img src="https://imgur.com/jR5hIRA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>STEP 46</b> - Open Security Logs To View Event for civ.venon Account.
</p>
<br />
