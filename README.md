                      Lab Program 1

Install Kali Linux and explain basic linux command and tools.

Steps-
•	Open Microsoft Edge
•	Search kali Linux download
•	Get Kali/Kali Linux
•	Select 64-bit
•	Click on virtual box
•	Wait for the downloading
•	Open the file
•	Click on right and select extract to the specific folder
•	Click on ok
•	Download the virtual tool box
•	Run the .exe file
•	Open the virtual box
•	Enter username: kali and password: kali
•	Open and give running or start go for terminal emulator


sudo apt update

sudo apt install

Linux commands are a type of Unix command or shell procedure. They are the basic tools used to interact with Linux on an individual level. Linux commands are used to perform a variety of tasks, including displaying information about files and directories. Linux operating system is used on servers, desktops, and maybe even your smartphone. It has a lot of command line tools that can be used for virtually everything on the system. All users should be familiar with most of these commands as they are required for most operating system tasks and computer programming. Here we have put all Basic Linux Commands that every Linux user (as a beginner) should know. These are not all that you should know, but these are the basic and most commonly used commands.

cal
pwd
ls
info
info ls
man ls
info pwd
          ls –help

                                     Lab Program 2
Install nmap on windows and perform basic operations identifying service, open ports, active hosts, operating system, vulnerabilities.
Installing nmap
•	 Open the browser and search ‘nmap download’, open the first website (url:”nmap.org”)
•	Click on window s option and download latest stable release version of nmap for windows.
“nmap-7.95-setup.exe”.
•	Its about 32MB file, after downloading it instrall in your system
To Perform Basic Operation
1.	Open command prompt and type “ipconfig” to get all the IP Addresses of your system.
C:\users\dell\ipconfig
Windows IP Configuration
Ethernet adapter ethernet 3:
IPV4 address…………….: 192.168.56.1

2.	Now copy any IP address from trhere example:
192.168.56.1 and paste that ip address in the target section inside the nmap program or application.

3.	After pasting it to the zenmap application click on scan button
Eg IP Address 192.168.56.1

4.	Wait until it get scanned and you get the below window.

To find open ports and active hosts
•	Open nmap and give the IP address intarget column and give the Zenmap command in command section as follows

i)	Target : 192.168.56.1
Command: nmap -p 80 192.168.56.1
Click on scan button
[p 80 stands for port 80]

ii)	Scanning the ports
Target : 192.168.56.1
Command: nmap -p 1-200 192.168.56.1
Click on scan button
We are scanning from port 1 to 200
[‘O Red ’ means it is closed and ‘O Green ’ means it is open]
 
iii)	Scan all the Common ports and provides the result
               Target : 192.168.56.1
               Command: nmap -F 192.168.56.1
Click on scan button
               F stands for most common ports


iv)	Target : 192.168.56.1
               Command: nmap -p- 192.168.56.1
Click on scan button
               p- scans all the ports of your system

v)	Target : 192.168.56.1
               Command: nmap -p- 192.168.56.1
Click on scan button
              This Scans all the TCP ip’s of your system

vi)	Target : 192.168.56.1
               Command: nmap -sU 192.168.56.1
Click on scan button
               This scans all the udp ports of your system

vii)	Target : 192.168.56.1
               Command: nmap -A 192.168.56.1
Click on scan button
               It scans, this will give the details of server and operating systems of your computer

viii)	Target : 192.168.56.1
               Command: nmap -sV 192.168.56.1
Click on scan button
                It gives the services and  OS details.





                                 Lab Program -3
Phishing Simulation (Google, Lucy and Gophish)
•	Search “get Gophish” on google.
•	Click the first link and go to the download section. It will redirect to Github.
•	Download the 64-bit zip file, and extract & setup on the system. Run Gophish.exe
•	Once open in cmd, open browser: goto http://127.0.0.1:3333 or given link.
•	Enter the data as given in the Example.
•	Set a new password.

Open Google Account Settings.
•	Search “APP PASSWORDS”
•	Create new Gophish App Password.
•	Copy the password or note it down.[important]

Once into Dashboard
	Goto Sending Profile
•	New Profile
•	Name: Chinmaya
•	SMTP from: Support@instagram.com
•	Host:smtp.google.com
•	Username: “Your Gmail”
•	Password: “App Password”
•	Save

	Goto Landing Page
•	Search Gophish Instagram Landing Page.
•	Copy Html code
•	Pack On Landing Page
Name: Chinmaya and paste the html code

	Goto Email template
•	New template
•	Name: Instagram mail
•	Sender: Support@instagram.com
•	Subject: “Your instagram account at risk”

	Goto Group and Users
•	Name: gophish_1
•	(From: FN: Chinmaya LN: KN) Email: “Your Email”
•	Position : It 
•	Save and Add
	Goto Campaign
•	Name: Phishing1
•	url: http://127.0.0.1:80
•	Save Changes and launch
•	Check results

	Output : Received the email of warning in gophish 






                                              Lab Program 4
Packet analysis using wireshark [sniffing using wireshark]
•	Goto goggle and search wireshark
•	Open the first link and select the first link init [windowX64installer]
•	Download 64bit installer
•	Complete the installation with agreeing to all the conditions.
•	Run the software.
•	Open the app through the search bar and you will get the interface or welcome to wireshark.
•	Click on the desired method or just click on the blue shark logo to start.
•	Select the Ethernet2 or Ethernet1 then it will run wait for a while and then click STOPS
•	Check how many packets have been downloaded and check the displays of packets.

















