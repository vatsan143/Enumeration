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

![311](https://github.com/Rajeshanbu/Enumeration/assets/118924713/12edcf5b-f42a-4366-9bd9-6ce521c005a6)

### filetype:
![32](https://github.com/Rajeshanbu/Enumeration/assets/118924713/2daef5ec-fa1c-49ee-9f05-344c32f4fd68)


### intext:
![33](https://github.com/Rajeshanbu/Enumeration/assets/118924713/6d83e607-510c-4a19-8b70-88fdefdbf4e0)


### inurl:
![34](https://github.com/Rajeshanbu/Enumeration/assets/118924713/7efc892e-31df-4b1a-87eb-726256754ac5)

### intitle:

![35](https://github.com/Rajeshanbu/Enumeration/assets/118924713/f7cdac62-7653-4ef1-9dde-5772c3072f9e)


### link:
![37](https://github.com/Rajeshanbu/Enumeration/assets/118924713/f050fed5-5492-4881-8875-1e0fd0f84190)

### cache:
![36](https://github.com/Rajeshanbu/Enumeration/assets/118924713/df0969c8-5472-4fae-bcba-04192dfda0d9)

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
![38](https://github.com/Rajeshanbu/Enumeration/assets/118924713/6ca6d32a-6e1d-426e-b760-391d1516c5b6)

![39](https://github.com/Rajeshanbu/Enumeration/assets/118924713/bc64174f-3f7f-4022-bba7-a7b6d892f88b)

### dnsenum
![311](https://github.com/Rajeshanbu/Enumeration/assets/118924713/fc8b34d5-1b49-4456-9f6d-458903a23386)

### smtp-user-enum
![313](https://github.com/Rajeshanbu/Enumeration/assets/118924713/04b7b430-c36c-4ebd-bb99-0fcb6ca8c5ed)

### nmap –script smtp-enum-users.nse

![314](https://github.com/Rajeshanbu/Enumeration/assets/118924713/85705cbc-f0c9-46c9-ba93-cee7016b8a80)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

