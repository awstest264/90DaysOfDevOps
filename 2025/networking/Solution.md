1 Understand OSI & TCP/IP Models

A OSI Model (7 Layers)
1. Physical – Sends raw data (cables, Wi-Fi).
   A highway enables cars to travel, the physical layer provides the medium for data transmission.

2. Data Link – Transfers data between devices (MAC, switches).
   A postal worker sorting letters based on addresses before delivery.
   
3. Network – Routes data (IP, routers).
   GPS - it finds the best route for data to reach its destination.
   
4. Transport – Ensures reliable delivery (TCP, UDP).
   Similar to sending a package via courier:
   TCP = Package with tracking
   UDP = Postcard without confirmation
   
5. Session – Manages communication (logins, sessions).

6. Presentation – Encrypts & formats data (SSL, compression).

7. Application – User-level services (HTTP, FTP, DNS).
   A web browser displaying a website using HTTP.


B TCP/IP Model (4 Layers)

1. Network Interface – Connects to hardware (Ethernet, Wi-Fi).
   Connecting a phone to Wi-Fi before accessing the internet.

2. Internet – Routes packets (IP, ICMP).
   Google Maps finding the best route for travel.

3. Transport – Ensures delivery (TCP, UDP).
   Choosing between a reliable package delivery (TCP) or a fast one (UDP).

4. Application – User services (Web, Email, FTP).
   Opening Gmail to send an email using SMTP
   
Key Differences

OSI: 7 layers, theoretical, structured.

TCP/IP: 4 layers, practical, used in the internet.

Example Online Shopping (Amazon, Flipkart)

1.Physical – Internet connection via Wi-Fi/mobile data.

2.Data Link – Device communicates with router.

3.Network – IP routes request to Amazon’s servers.

4.Transport – TCP ensures order details are sent securely.

5.Session – Keeps you logged in while browsing.

6.Presentation – Encrypts payment details (SSL/TLS).

7.Application – Website processes order via HTTPS.




2. Protocols and Ports for DevOps
   

1.HTTP(80)   - HyperText Transfer Protocol
               Browsing websites (unencrypted) 

2.HTTPS(443) - Secure HTTP
               Secure web browsing with encryption 
  
3.FTP(21)	   - File Transfer Protocol
               Transferring files between computers 

4.SFTP(22)	 - Secure File Transfer Protocol
               Secure file transfer (uses SSH) 

5.SSH(22)	   - Secure Shell	22
               Remote login & secure command execution 

6.DNS(53)	   - Domain Name System	53
               Converts domain names to IP addresses 

7.SMTP(25)	 - Simple Mail Transfer Protocol
               Sending emails 

8.POP3(110)	 - Post Office Protocol v3
               Retrieving emails from a server 

9.IMAP(143)	 - Internet Message Access Protocol
               Synchronizing emails across devices 

10.RDP(3389)	 - Remote Desktop Protocol
               Accessing a remote Windows PC 

11.Telnet(23) - Terminal Network	
               Unsecure remote login (deprecated) 

12.SNMP(161)	 - Simple Network Management Protocol
               Monitoring & managing network devices 

13.DHCP(67/68)- Dynamic Host Configuration Protocol
               Assigning IP addresses automatically 

14.NTP(123)	 - Network Time Protocol
               Synchronizing time across devices 


1.Automation - SSH, SFTP, DHCP help in managing infrastructure-as-code (Terraform, Ansible).

2.Monitoring & Logging - SNMP, NTP, SMTP ensure system health tracking.

3.Security & Compliance - HTTPS, SSH, and SFTP protect deployments and communications.

4.CI/CD Pipelines - DNS, HTTP, and FTP ensure smooth software delivery.
