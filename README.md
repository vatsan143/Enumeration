# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

### Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

#### site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

### filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



### intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


### inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

### intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

### link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

### cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## output:
### site:
![Screenshot 2024-04-03 082413](https://github.com/Rajeshanbu/Enumeration/assets/118924713/54a0a44d-46e2-44eb-b4d2-c70fdbe9f6f2)

### filetype:
![Screenshot 2024-04-03 082555](https://github.com/Rajeshanbu/Enumeration/assets/118924713/52967193-0fe7-4683-a98d-a5dcdf1a2eee)

### intext:
![Screenshot 2024-04-03 082701](https://github.com/Rajeshanbu/Enumeration/assets/118924713/15cb8bb9-a194-4672-af43-3b1c3f670790)

### inurl:
![Screenshot 2024-04-03 082803](https://github.com/Rajeshanbu/Enumeration/assets/118924713/fd2158de-f406-4400-8bdd-358ce8ffb85e)

### intitle:
![Screenshot 2024-04-03 083059](https://github.com/Rajeshanbu/Enumeration/assets/118924713/e3c4b4d1-f2ab-41c0-9b94-affe1ca62704)


### link:
![Screenshot 2024-04-03 084134](https://github.com/Rajeshanbu/Enumeration/assets/118924713/f28c6bea-c40d-46c3-afb2-918d8a19309e)
### cache:
![Screenshot 2024-04-03 083912](https://github.com/Rajeshanbu/Enumeration/assets/118924713/135bb840-1c2e-4e07-86a8-efa64e37712b)
## DNS Enumeration:
### DNS Recon
provides the ability to perform: Check all NS records for zone transfers Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT) Perform common SRV Record Enumeration Top level domain expansion

### dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record). Get the namservers (threaded). Get the MX record (threaded). Perform axfr queries on nameservers and get BIND versions(threaded). Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”). Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded). Calculate C class domain network ranges and perform whois queries on them (threaded). Perform reverse lookups on netranges (C class or/and whois netranges) (threaded). Write to domain_ips.txt file ip-blocks. This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

### smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same

Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25 telnet 25 to connect and issue appropriate commands

nmap –script smtp-enum-users.nse
The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

### OUTPUT:
## DNS Recon
![Screenshot 2024-04-03 103834](https://github.com/Rajeshanbu/Enumeration/assets/118924713/a4bb66e7-50f9-4d7c-98aa-d40df74b75c6)
![Screenshot 2024-04-03 104150](https://github.com/Rajeshanbu/Enumeration/assets/118924713/510b72e8-e523-4373-9cb0-ef0e99df0674)

### dnsenum
![Screenshot 2024-04-03 104331](https://github.com/Rajeshanbu/Enumeration/assets/118924713/5dc27af7-43eb-4900-8f61-ee5aec6432fc)

### smtp-user-enum
![Screenshot 2024-04-03 104727](https://github.com/Rajeshanbu/Enumeration/assets/118924713/3510a49e-1516-47bc-a53c-9268736d89a5)

### nmap –script smtp-enum-users.nse
![Screenshot 2024-04-03 110039](https://github.com/Rajeshanbu/Enumeration/assets/118924713/12b48644-95d1-4d62-86a6-18e8520196fb)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

