# <center>**Case Study #2**</center><br><center> By Julian Mato-Hernandez & Evan Jurdan </center>

# Document Outline
- [Document Outline](#document-outline) 
- [Executive summary](#executive-summary)
- [Introduction](#introduction)
    - [Project Outline](#project-outline)
- [Requirements Analysis](#requirements-analysis)
    - [General Requirements](#general-requirements)
    - [Hardware Requirements](#hardware-requirements)
    - [Software Requirements](#software-requirements)
- [Customer Meeting Synopsis](#customer-meeting-synopsis)
- [Network Structure](#network-structure)
    - [Network Border](#network-border)
    - [Network Core](#network-core)
    - [Network Access](#network-access)
    - [Network WLAN](#network-wlan)
    - [Servers and Services](#servers-and-services)
    - [Security and Network Managment](#security-and-network-managment)
- [Network Maps](#network-maps)
    - [Logical](#logical)
    - [Phisical with Devices](#phisical-with-devices)
    - [Redundancies](#redundancies)
    - [Security Devices](#security-devices)
- [Budget and Justification](#budget-and-justification)
    - [Justification](#justification)
    - [Total Cost](#total-cost)
    - [General BOM](#general-bom)
    - [Azure BOM](#azure-bom)
- [Scalability](#scalability)
- [GNS3 Models and Descriptions](#gns3-models-and-descriptions)
- [Performance Metrics Explaned](#performance-metrics-explaned)
- [Network Performance Analasis](#network-performance-analasis)
- [Optimizations Suggested](#optimizations-suggested)
- [Optomized Examples](#optomized-examples)
- [Summary](#summary)
- [Appendix A Q&A](#appendix-a-qa)
- [Appendix B Cost Analasys Sources](#appendix-b-cost-analasys-sources)
<br>
<br>
<br>

# Executive summary:
For this network the customer needed a nearly complete ground up design of their network. This network contains new equipment (PC, Laptops, Infrastructure, and security devices) along with a host of software (Email, Storage, Network Monitoring, and security). The customer needs these basic services to be as reliable and functional as possible. We will be providing a cloud based work environment centered around Microsoft Azure, this will provide AD, Storage, backups, email, notifications, and parts of security. Along with this cloud infrastructure we will be providing a Full unified wired and wireless network to both buildings. 
<br>
<br>
<br>

# Introduction:
    
## Project Outline -      
<br>
<br>
<br>

# Requirements Analysis:
## General Requirements -     
This building had only a small network in acounting. The buisness needed to have Computers for employees and secure storage and trasfer of confidential records. They are a government buisness and need their data to be secure but they also needed to be able to share between certaint departments and better analize data. 
<br>
<br>

## Hardware Requirements -     
The company needed an entire network from scratch. They needed a desktop computer per employee as well as a laptop per employee. There were also 54 micro computers to put in classroom labs. Each desktop and micro computer needed a monitor and periferals. We needed to design a network and purchase the hardware to put it in place so we had to buy switches, a support server, and access points to implement the network that they wanted. We planned all of the cat6 cable runs throughout the building as well as the fiber lines connecting our layer 3 switches and the fiber connection under the road to the other building. They wanted a lot of office printers and a larger printer/scanner/coppier, in order to better fit in the buget not everyone could get individual printers but the people we didn't give a printer to are in extream close proximity to the large comunal printer. We mapped where there should be power drops, each power drop would have 4 connections and each internet drop would have 2 connections. 
<br>
<br>

## Software Requirements -     
Since it is a government organization they needed a secure network and a secure storage. the AZURE suite had all of the components needed to build a network that was secure and accessable. We have secure storage set up and backed up with a seperate storage for accounting for added security. AZURE also has active directory so our network has security that insures only people who are allowed to look at or edit something are allowed to view it. We also have office 365 for each person so that they have access to word prossesing, spreadsheet, and presentation software to aid in the recording of information, the analizing of data, and the formation of presentations.  
<br>
<br>
<br>

# Customer Meeting Synopsis:

# Network Structure:
## Network Border -     
<br>
<br>

## Network Core -     

<br>
<br>

## Network Access -     

<br>
<br>

## Network WLAN -     

<br>
<br>

## Servers and Services -     

<br>
<br>

## Security and Network Managment -     

<br>
<br>
<br>

# Network Maps:
## Logical -     

<br>
<br>

## Phisical with Devices -     

<br>
<br>

## Redundancies -     

<br>
<br>

## Security Devices -     

<br>
<br>
<br>

# Budget and Justification:
## Justification -     

<br>
<br>

## Total Cost -     
#### Total First Month in USD = $4,309.56

#### Total for reocuring payments per year in USD = $51,714.68

#### Total OTC in USD = $118,140.66

### **First Month + OTC in USD =$122,450.22**
<br>
<br>

## General BOM -     
|Amount|Product Name |Manufacturer|Description|Single Unit Cost in USD|Billing Period|Cloud Y/N|Expense Per Month in USD|Expense Per Year in USD|OTC in USD|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|9|Central one device - 1 year|HPE / Aruba||$11.60|Montly|Y|$104.40|$1,252.80|N/A|
|4|AP-505|HPE / Aruba||$506.00|One Time|N|||$2,024.00|
|1|2530 8G PoE+ (J9780A)|HPE / Aruba||$792.00|One Time|N|||$792.00|
|2|6100 24G PoE 4SFP+ (JL677A)|HPE / Aruba||$2,406.49|One Time|N|||$4,812.98|
|2|3810M 16SFP+ (JL075A)|HPE / Aruba||$4,524.12|One Time|N|||$9,048.24|
|27|HP wireless keyboard and mouse|HP||$20.00|One Time|N|||$540.00|
|54|ThinkCenter M70q Tiny|Lenovo||$478.00|One Time|N|||$25,812.00|
|27|ThinkPad L14 AMD (14”)|Lenovo||$593.55|One Time|N|||$16,025.85|
|27|ThinkPad Ultra Docking Station|Lenovo||$199.99|One Time|N|||$5,399.73|
|3|6U Net Rack|NavePoint||$222.44|One Time|N|||$225.44|
|1|18U Rack Enclosure|NavePoint||$866.49|One Time|N|||$866.49|
|27|Office 365 with Enterprise Outlook|Microsoft||$22.00|Montly|Y|$594.00|$7,128.00||
|1|Azure|Microsoft|||Montly|Y|$2,961.16|$35,533.88||
|2|Firebox M290 Firewall - 8 Port|Watchguard Technologies||$1,232.39|One Time|N|||$2,464.78|
|27|CP-7841-K9|Cisco||$165.00|One Time|N|||$4,455.00|
|8|HL-L2325DW|Brother||$99.99|One Time|N|||$799.92|
|1|Versalink C405DNM|Xerox||$695.00|One Time|N|||$695.00|
|81|E205W-1600 20”|Sceptre||$116.00|One Time|N|||$9,396.00|
|2|Tripp Lite SMART1500LCD UPS|Tripp Lite||$248.71|One Time|N|||$250.71|
|2|EMC PowerEdge R240|Dell||$1,445.99|One Time|N|||$2,891.98|
|2|16TB Exos X18|Seagate||$339.97|One Time|N|||$679.94|
|3|YubiKey 5 NFC FIPS – 10 Pack|Yubico||$550.00|One Time|N|||$1,650.00|
|5|1000ft Shielded Gray Cat6|cablewholesale||$234.52|One Time|N|||$1,172.60|
|578|Fiber Optic cable & Install / per foot|||$3.00|One Time|N|||$1,734.00|
|4536|Cat 6 installation & keystone’s / per foot|||$1.50|One Time|N|||$6,804.00|
|20|Inter Campus Tunnling / per foot|||$200.00|One Time|N|||$4,000.00|
|13|Door Acess Control|||$1,200.00|One Time & Monthly|N|$650.00|$7,800.00|$15,600.00|

<br>
<br>

## Azure BOM -     
|Service type|Use|Region|Description|Estimated monthly cost|
|:---:|:---:|:---:|:---:|:---:|
|Storage Accounts|Acounting|East US|File Storage, Transaction Optimized Performance Tier, General Purpose V2, LRS Redundancy, 2 TB of Data at-rest, 1 TB Snapshots, 1 x 10,000 Write Transactions, 1 x 10,000 List Transactions, 1 x 10,000 Read Transactions, 1 x 10,000 Other Operations, 1 Additional Sync Server(s)|$189.35|
|Azure Backup|Accounting Backup|East US|Azure Files, 1 Instance(s) x 2 TB, LRS Redundancy, Low Average Daily Churn, 1 TB Average monthly snapshot usage data|$121.75|
|Storage Accounts|Company wide|East US|File Storage, Transaction Optimized Performance Tier, General Purpose V2, LRS Redundancy, 6 TB of Data at-rest, 2 TB Snapshots, 1 x 10,000 Write Transactions, 1 x 10,000 List Transactions, 1 x 10,000 Read Transactions, 1 x 10,000 Other Operations, 4 Additional Sync Server(s)|$511.55|
|Azure Backup|Company Wide Backup|East US|Azure Files, 1 Instance(s) x 7 TB, LRS Redundancy, Low Average Daily Churn, 1 TB Average monthly snapshot usage data|$72.80|
|Azure ExpressRoute|||ExpressRoute, Zone 2, Premium, Metered; 50 Mbps Circuit X 1 circuit, 1 TB in Additional Outbound Data Transfer; Global Reach Add On:|$206.20|
|Microsoft Sentinel||East US|Logs ingested - 7 GB Basic logs per day, 3 GB Analytics logs per day; Azure Monitor Retention - 3 months of Data Retention, 0 months of Data Archive; Azure Monitor Data Restore - 500 Basic log queries per day, 1000 GB data scanned per query, 2000 GB Data Restored, 0 days data restored; Azure Monitor Search Queries and Search Jobs – 0 queries per day, 0 GB data scanned per query of Search Queries, 0 queries per day, 0 GB data scanned per query of Search Jobs|$585.50|
|Azure Active Directory (Azure AD)||East US|Premium P1 - 19 users, Premium P2 - 10 users, Enterprise tier, User forest - 100 Hours, Resource forest - 50 Hours.|$264.00|
|Azure Cost Management and Billing|||No charge for managed Azure spend. Additional premium capabilities are available at no cost through December 2018 when they will become paid features. 1% of managed spend for AWS and Google Cloud Platform.|$0.00|
|Notification Hubs||East US|Basic tier, 1 million additional pushes|$10.00|
|Support|||Support|$1,000.00|

<br>
<br>
<br>

# Scalability:

<br>
<br>
<br>

# GNS3 Models and Descriptions:

<br>
<br>
<br>

# Performance Metrics Explaned:

<br>
<br>
<br>

# Network Performance Analasis:

<br>
<br>
<br>

# Optimizations Suggested:

<br>
<br>
<br>

# Optomized Examples:

<br>
<br>
<br>

# Summary:

<br>
<br>
<br>

# Appendix A Q&A:

<br>
<br>
<br>

# Appendix B Cost Analasys Sources:

<br>
<br>
<br>
