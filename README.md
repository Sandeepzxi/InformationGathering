# Ex-02 InformationGathering
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

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="802" height="445" alt="image" src="https://github.com/user-attachments/assets/4f7ab0ba-79da-48af-b3c6-8a50bcf3dfb3" />


### Finding Hosting Company :
<img width="1919" height="1048" alt="image" src="https://github.com/user-attachments/assets/f1606738-abc2-484c-a14f-a66376f4a328" />


### History of the website :
<img width="766" height="415" alt="image" src="https://github.com/user-attachments/assets/8f14a6a6-eacb-44b1-afbc-31ff71447d9c" />


### ping command :
<img width="487" height="295" alt="image" src="https://github.com/user-attachments/assets/33f72bcb-9775-4aab-9ef9-5022243bdfb2" />


### whois :
<img width="1420" height="609" alt="image" src="https://github.com/user-attachments/assets/4de4883c-ac60-4321-985d-81b32fc335ae" />


### netcat :
<img width="618" height="274" alt="image" src="https://github.com/user-attachments/assets/392da415-0dca-44dc-907a-25809cd1ff8b" />


### nmap :
<img width="716" height="177" alt="image" src="https://github.com/user-attachments/assets/721787ac-837f-4e37-b68f-dc7ac102c673" />


### whatweb :
<img width="1408" height="115" alt="image" src="https://github.com/user-attachments/assets/6804fe36-ba29-468a-85f9-db39a1e95f07" />


### httprint :
<img width="735" height="622" alt="image" src="https://github.com/user-attachments/assets/23cb4fbf-1755-4a98-a2ac-99b3895c7a7e" />


### TCP traceroute :
<img width="972" height="196" alt="image" src="https://github.com/user-attachments/assets/bc20b10e-96bc-4f90-a8ea-0a5b142c8c66" />


### UDP traceroute :
<img width="1012" height="350" alt="image" src="https://github.com/user-attachments/assets/7e9e5815-8807-4946-9632-afd9355f4c3d" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
