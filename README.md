# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

## AIM:

To use Google for gathering information and perform enumeration of targets

### STEPS:

#### Step 1:

Install kali linux either in partition or virtual box or in live mode

#### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


#### Step 3:
Open terminal and try execute some kali linux commands

### Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

### Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

#### site:
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain youtube.com



![Screenshot 2025-03-15 132114](https://github.com/user-attachments/assets/c4e7ce8f-0a71-4608-a983-4a0bbee9b370)




#### filetype: 

![Screenshot 2025-03-15 132200](https://github.com/user-attachments/assets/4cdfd1cc-bb27-4c33-a476-aa691797e066)

This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

#### intext:
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![Screenshot 2025-03-15 132252](https://github.com/user-attachments/assets/cb8ac0ce-d1a7-4af2-8acb-518c273ec8bd)



#### inurl:
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![Screenshot 2025-03-15 132357](https://github.com/user-attachments/assets/edbad9a1-0111-4801-b28a-ace0b3672b0e)


#### intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![Screenshot 2025-03-15 132446](https://github.com/user-attachments/assets/7f360b23-4d19-4f39-a24d-8f48284a8dff)



#### link:
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![Screenshot 2025-03-15 132543](https://github.com/user-attachments/assets/5cc69c99-28c9-465a-8aab-b8d941a3ef58)

 
### DNS Enumeration


#### DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
#### OUTPUT:
![Screenshot 2025-03-15 133450](https://github.com/user-attachments/assets/401453d1-361b-46a6-a482-6ff267d41d67)


#### dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
![Screenshot 2025-03-15 133702](https://github.com/user-attachments/assets/8d68dd5a-fd57-4a30-bda3-9ef1874fc1c5)



#### smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

![Screenshot 2025-03-15 134805](https://github.com/user-attachments/assets/363d7de9-5f93-4cb1-bd07-4d55d5ff01bc)




#### Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
#### Output
  
![WhatsApp Image 2025-03-15 at 14 48 44_7ad1bd51](https://github.com/user-attachments/assets/219d9038-7f08-48ca-a0be-e5bed6221145)


#### nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


#### OUTPUT:
 
![Screenshot 2025-03-15 135545](https://github.com/user-attachments/assets/ee9104eb-6a8a-4cb7-9b7c-ba91d2da0b4e)

 

### RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully



