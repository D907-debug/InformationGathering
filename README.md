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
<img width="1158" height="1093" alt="image" src="https://github.com/user-attachments/assets/5cb0d601-fb87-4ae6-a8f8-4b3da8350985" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output


<img width="775" height="368" alt="image" src="https://github.com/user-attachments/assets/a9e93cfc-b79c-42ea-8878-8f02fc4d1a34" />


## Finding Hosting Company
get further detail by using ip2location.com website.
##output



<img width="1534" height="934" alt="image" src="https://github.com/user-attachments/assets/45181b1d-888e-4445-9ad5-678d5f8e95e4" />
## History of the website:
## output
https://web.archive.org/

<img width="1359" height="1015" alt="image" src="https://github.com/user-attachments/assets/690b0861-13a0-4c54-9be8-a6f72e03ec3a" />
# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com




## nmap:
###output


## Whatweb
### output


## httprint
### output




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output


## UDP Traceroute:
sudo traceroute -U www.google.com
## output



## ICMP Traceroute:
sudo traceroute  www.google.com
## output






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
