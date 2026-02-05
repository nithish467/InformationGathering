# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output 

<img width="603" height="145" alt="Screenshot From 2026-01-31 12-39-03" src="https://github.com/user-attachments/assets/664eb8fe-8c67-4a9f-a366-dbd0b354f835" />




## Finding Hosting Company
get further detail by using ip2location.com website.
##output



## History of the website:
## output
https://web.archive.org/


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com



## nmap:
### output
<img width="801" height="270" alt="Screenshot From 2026-01-31 12-18-35" src="https://github.com/user-attachments/assets/8fbfd33f-957a-4687-ab5a-cdfe86b93dfc" />


## Whatweb
### output
<img width="1689" height="141" alt="Screenshot From 2026-01-31 12-24-03" src="https://github.com/user-attachments/assets/9bbf4c33-889a-4d3e-8f84-674e333e8525" />


## httprint
### output
<img width="672" height="104" alt="Screenshot From 2026-01-31 12-16-37" src="https://github.com/user-attachments/assets/bb1fb9fa-cac4-419e-8e33-5804f2deb947" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.sony.com
## output
<img width="844" height="116" alt="Screenshot From 2026-01-31 12-42-14" src="https://github.com/user-attachments/assets/8be46a61-5898-47ee-a83a-94059414b3d8" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="619" height="620" alt="Screenshot From 2026-01-31 12-17-08" src="https://github.com/user-attachments/assets/d1a2b275-c29c-40a7-91db-b83fac0c004d" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="619" height="620" alt="Screenshot From 2026-01-31 12-16-52" src="https://github.com/user-attachments/assets/62ab1d72-e9b2-4936-8ba2-9d975e782b8b" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
