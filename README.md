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
<img width="603" height="145" alt="image" src="https://github.com/user-attachments/assets/61e70de0-9c4d-496e-90bd-0410e9581d46" />

<img width="307" height="292" alt="Screenshot From 2026-01-31 12-22-47" src="https://github.com/user-attachments/assets/371e8144-d71a-4911-8284-959ed5602c43" />





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
###output
<img width="801" height="270" alt="Screenshot From 2026-01-31 12-18-35" src="https://github.com/user-attachments/assets/7a7e7178-3441-40bc-9a4b-72465eae1ee2" />



## Whatweb
### output
<img width="1689" height="141" alt="Screenshot From 2026-01-31 12-24-03" src="https://github.com/user-attachments/assets/fb1ba982-4ac4-45e2-b5f4-1b76847c1294" />



## httprint
### output
<img width="672" height="104" alt="Screenshot From 2026-01-31 12-16-37" src="https://github.com/user-attachments/assets/0f7340cc-b4d3-415e-89bb-00d24cd69308" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="844" height="116" alt="image" src="https://github.com/user-attachments/assets/0121378f-b19c-4639-81dd-b22c9badc850" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="619" height="620" alt="Screenshot From 2026-01-31 12-17-08" src="https://github.com/user-attachments/assets/9d9031ee-cd52-455e-b056-eb0c53126fc3" />




## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="619" height="620" alt="Screenshot From 2026-01-31 12-16-52" src="https://github.com/user-attachments/assets/0da88288-7079-4193-a54a-86d09130876f" />







## RESULT:
The information gathering techniques tools/procedure were  identified successfully
