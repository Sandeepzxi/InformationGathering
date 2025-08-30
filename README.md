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
<img width="721" height="865" alt="image" src="https://github.com/user-attachments/assets/ce94690a-3ea3-4aa0-baa1-740fd9d639c6" />


### whois :
<img width="802" height="445" alt="image" src="https://github.com/user-attachments/assets/645403b4-b53a-40f1-9612-5cc54ff1f851" />


### netcat :
<img width="874" height="93" alt="image" src="https://github.com/user-attachments/assets/eb742369-544c-4d19-a300-c0b7849b3632" />


### nmap :
<img width="762" height="251" alt="image" src="https://github.com/user-attachments/assets/b241cc3d-dd56-47b1-8ce7-9500b7a96119" />


### whatweb :
<img width="762" height="611" alt="image" src="https://github.com/user-attachments/assets/9ae6eebb-79c2-421d-9288-81b53ad6221e" />


### httprint :
<img width="763" height="382" alt="image" src="https://github.com/user-attachments/assets/7653b0a5-2518-45d5-b17c-c83ed40a8af6" />


### TCP traceroute :
<img width="765" height="681" alt="image" src="https://github.com/user-attachments/assets/f32cfa87-5be5-431c-b923-906d40b506a1" />


### UDP traceroute :
<img width="769" height="574" alt="image" src="https://github.com/user-attachments/assets/c3911f8f-8308-4d76-9e3a-7bcde22ec16c" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
