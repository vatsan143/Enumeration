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

![321869206-12edcf5b-f42a-4366-9bd9-6ce521c005a6](https://github.com/vatsan143/Enumeration/assets/147368204/0f52c9ab-d0cb-4cba-a58c-3f1476b68569)

### filetype:

![321872255-2daef5ec-fa1c-49ee-9f05-344c32f4fd68](https://github.com/vatsan143/Enumeration/assets/147368204/45bc5174-6cd3-4b12-ba8c-a889dd5b7e48)

### intext:

![321872268-6d83e607-510c-4a19-8b70-88fdefdbf4e0](https://github.com/vatsan143/Enumeration/assets/147368204/24ce8ed8-3739-4ea4-94c9-240c9ef8345e)

### inurl:

![321872289-7efc892e-31df-4b1a-87eb-726256754ac5](https://github.com/vatsan143/Enumeration/assets/147368204/80782a77-f299-4576-ac16-20100c9a396f)

### intitle:


![321872331-f7cdac62-7653-4ef1-9dde-5772c3072f9e](https://github.com/vatsan143/Enumeration/assets/147368204/9758378b-61a3-4fa6-a16b-25200a704991)

### link:
![321872356-f050fed5-5492-4881-8875-1e0fd0f84190](https://github.com/vatsan143/Enumeration/assets/147368204/866dadca-c088-4d8c-8d3d-7895d17b0309)

### cache:
![321872376-df0969c8-5472-4fae-bcba-04192dfda0d9](https://github.com/vatsan143/Enumeration/assets/147368204/fa309948-7b86-4870-a4c1-370970f8fef8)

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
![321872465-6ca6d32a-6e1d-426e-b760-391d1516c5b6](https://github.com/vatsan143/Enumeration/assets/147368204/efd39ea1-8e53-44c7-bd72-394d9ee9011d)
![321872486-bc64174f-3f7f-4022-bba7-a7b6d892f88b](https://github.com/vatsan143/Enumeration/assets/147368204/c16ee69e-ef87-40bd-a166-6986e0ba95f8)


### dnsenum
![321873177-fc8b34d5-1b49-4456-9f6d-458903a23386](https://github.com/vatsan143/Enumeration/assets/147368204/2b42ba21-88b0-468d-ab36-310bebaaff58)

### smtp-user-enum
![321873215-04b7b430-c36c-4ebd-bb99-0fcb6ca8c5ed](https://github.com/vatsan143/Enumeration/assets/147368204/1d0902ec-a4ce-4c39-93e6-3026c589d220)

### nmap –script smtp-enum-users.nse

![321872546-85705cbc-f0c9-46c9-ba93-cee7016b8a80](https://github.com/vatsan143/Enumeration/assets/147368204/13894d99-91e9-49d4-98d0-e8e8608cdb79)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

