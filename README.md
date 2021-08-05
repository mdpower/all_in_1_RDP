## RDP Windows, Ubuntu & MacOS



[![OS - Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/en-us/windows-server)
[![OS - Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)
[![OS - MAcOS](https://img.shields.io/badge/MacOs-000000?style=for-the-badge&logo=Apple&logoColor=)](https://www.apple.com/macos/server/)

> ***⚠️ WARNING***  
* THIS IS ONLY FOR EDUCATIONAL PURPOSES
* DON'T USE FOR MINING OR ILLEGAL USE
* Not for Cryptocurrency Mining.                                              
* Don't close the starter terminal (Connected to Github).
-----------------
<details>
  <summary>Tunnel Servers.</summary>

* us - United States (Ohio)
* eu - Europe (Frankfurt)
* ap - Asia/Pacific (Singapore)
* au - Australia (Sydney)
* sa - South America (Sao Paulo)
* jp - Japan (Tokyo)
* in - India (Mumbai)
-----------------
</details>

### Deloy and Run
<details>
  <summary>MacOS Install and Run</summary>
<br>
    
1. go to `Actions` Tab and select one of system workflow.

2. Click `Run Workflow` button on the left of `This workflow has a workflow_dispatch event trigger` line.

3. Wait until a few minutes.

4. Go to https://dashboard.ngrok.com/status/tunnels and check if theres a one online tunnel running.

5. Copy the link(**without tcp://**) and go to VNC Viewer(Download and install it), input the link to connect area u copied from the website.

6. Fill in those login info, within username `Avishkar`and password from `VNC_PASSWORD` you typed.

7. Enjoy!
------
</details>

<details>
    <summary>Windows 10</summary>
<br>

1. First, start the actions of Windows 10 System.    
2. Second, Go to https://dashboard.ngrok.com/status/tunnels and check if theres a one online tunnel running.
3. Go to Windows Remote Desktop Connection app or Microsoft Remote Desktop software to connect to windows 10 VPS.
4. Username For Windows RDP is `runneradmin`
5. ENJOY!
------
</details>

<details>
    <summary>Linux</summary>
<br>

1. First, start the actions of Linux System.
2. Second, Copy the link from the console
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/0F804C5F-FE8F-45FA-9720-F91F212597DF.png" >
3. Go to MacOS Terminal or Windows CMD Terminal or else ssh client and enter command provided. Enter your ssh password then.
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/78FE6C5A-7270-4986-AB8F-57EC4C9B4F44.png" >
4. ENJOY!
------
</details>

</details>

  <details>
    <summary>Ngrok (RDP)</summary>


* Click Fork in the right corner of the screen to save it to your Github.
* Visit https://dashboard.ngrok.com to get **Ngrok Auth Token**.
* In Github go to Action> Windows (Ngrok RDP)> Run workflow.
* In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into.
* Password minimum 8-10 with numbers and characters leave blank if you want to use automatic password.
* Press Run workflow.
* Reload the page and press Windows (Ngrok RDP)> build.
* Press the down arrow on Account for Connect to your RDP to get IP, User, Password.
------

</details>

<details>
    <summary>Google Remote Desktop.</summary>

------

* Visit https://remotedesktop.google.com/headless to get **Google Remote Desktop Code**.
* Click Start> Next> Allow> Copy Windows (Windows PowerShell) / Ubuntu (Debian Linux).
* In Github go to Action> Windows/Ubuntu (Google Remote Desktop)> Run workflow.
* In Value: Paste Code.
* Press Run workflow.
* Reload the page and press Windows/Ubuntu (Google Remote Desktop)> build.
* Wait and visit https://remotedesktop.google.com/access to connect rdp.

------

</details>

<details>
    <summary>Ngrok (NVC Viewer)</summary>

**❕ TIPS**  
Use the te teamviewer to avoid the lag.
  * Visit https://www.realvnc.com/en/connect/download/viewer to download **NVC Viewer**.
* Install Software.
* Visit https://dashboard.ngrok.com to get **Ngrok Auth Token**.
* In Github go to Action> MacOS (Ngrok VNC Viewer)> Run workflow.
* In Value: visit https://dashboard.ngrok.com/auth/your-authtoken Copy and Paste Your Authtoken into.
* Password minimum 8-10 numbers/characters.
* Press Run workflow.
* Reload the page and press MacOS (Ngrok VNC Viewer)> build.
* Press the down arrow on IP for Connect to your RDP to get IP.
* Open VNC Viewer put ip in the field "Enter a VNC Server Address or search" and enter too connect.

-----------------

</details>

### Screenshots:

<details>
    <summary>Windows 10</summary>
<br>
    
- Windows 10 Version
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/268600af-c8b9-47cf-b5dd-d1c1ed6d9ce9.png">

- Windows 10 Task Manager
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/0cf98258-a6fe-46bb-ac9a-ee4bb3037e3a.png" >

- Windows 10 Device Manager
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/d32cf285-5ecf-4cce-a52a-5cb54fb130c7.png">

- Windows 10 Device Specification
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/e1852b80-d550-44f3-b619-86ea82902bb4.png">
    
</details>

<details>
    <summary>Ubuntu (SSH Version)</summary>
<br>

1. Click **Run Workflox**
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/96644176-D760-47D4-BED2-C47E62A6763F.png" >

2. Copy ssh with url
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/0F804C5F-FE8F-45FA-9720-F91F212597DF.png" >

3. Open cmd or Terminal from your windows/MacOS or Linux, and type command provided by github actions boxes.
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/78FE6C5A-7270-4986-AB8F-57EC4C9B4F44.png" >

type **yes** from the connect, and then type your ssh password by secrets of LINUX_USER_PASSWORD u have set.

4. Type **sudo -i** for root permission and type your password.
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/E5527744-1ED1-4550-8867-EF4EC76D6895.png" >

5. Enjoy having your FREE linux SSH VPS and type any command you want.(but only 6 hours)
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/E6E9EA63-AC24-4FDB-AAF9-8B509658440A.png" >

</details>

<details>
    <summary>Ubuntu (Desktop Remote Version)</summary>
<br>

- Desktop Screenshot
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/4EB9C2FF-9D03-4998-A440-D7716A0F7CD0.png" >

- Linux Chrome
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/09F0A4CF-9B30-44CD-8DC4-139D03DFC2CC.png" >

- Install any apps you want :)
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/A0886141-DF1E-4379-88E7-F00EDAD87D0E.png">

</details>

<details>
    <summary>MacOS</summary>
<br>

- Desktop Screenshot
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.32.41%20AM.png" >

- Settings
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.32.21%20AM.png" >

- RAM
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.32.58%20AM.png" >

- Storage
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.33.18%20AM.png" >

- Pre-Installed Apps
<img src="https://raw.githubusercontent.com/RealKoolisw/image/main/VirtualMachine-GHAction/sceenshots/Screenshot%202021-02-23%20at%207.34.10%20AM.png" >

  
