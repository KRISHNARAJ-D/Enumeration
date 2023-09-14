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

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
## Output:

![239720288-29828d11-353b-40d3-8951-61a42d9c029f](https://github.com/KRISHNARAJ-D/Enumeration/assets/119559695/eac27eaf-9571-4eb9-a785-6d54d855104c)


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## Output:

![239720300-f169a7de-0f7f-4b8c-b402-ccaa6ea6a907](https://github.com/KRISHNARAJ-D/Enumeration/assets/119559695/95369c38-c7a6-4ebe-84c1-1c5338bb4ac6)




intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## Output:
![239720307-f7716744-5455-463e-b0a0-3a44821e70af](https://github.com/KRISHNARAJ-D/Enumeration/assets/119559695/286c29c1-684a-4cbe-b435-b617f9402646)



inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## Ouput:
![239720312-61b83322-2aba-44f3-9a90-dc9bb3fe6175](https://github.com/KRISHNARAJ-D/Enumeration/assets/119559695/1e381ee8-793b-4dc6-b3b0-0b677b03bb47)



intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## Output:
![239720322-cbda231f-5058-4343-8541-014cc1c5729c](https://github.com/KRISHNARAJ-D/Enumeration/assets/119559695/1842e4a5-f1fd-4f7c-aa66-ae4a864beaf5)


link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## Output:

![239720329-bf1840b8-075d-497e-8f1c-4ca6d8327982](https://github.com/KRISHNARAJ-D/Enumeration/assets/119559695/4ef845b4-5c85-4e81-839a-8981a1621476)


cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## Output:

![239720337-e127c95b-a133-42d4-aa3d-a833faa3aad0](https://github.com/KRISHNARAJ-D/Enumeration/assets/119559695/971d22ca-bde9-4b13-9cf3-876409ffcb48)


 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion


## dnsenum
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


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  

  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.





## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
