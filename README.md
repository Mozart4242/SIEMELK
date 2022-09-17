# SIEMELK

<p align="center">
 <img alt="SIEMELK Logo" src="images/SIEMELK..png">
</p>

📌 SIEMELK is a customizable and scalable Security Monitoring Software Solution that is accessible to small, medium amd enterprise organizations.

📌 SIEMELK is built on the best of Open Source tools with extra functionality, integration stability and correlation providing enriching data from the SIEM.

📌  SIEMELK IS **NOT** AN **OPEN-SOURCE** PLATFORM

<h1 align="center">
Lets go beyond a SIEM
</h1>


## [Product Overview](features.md)

## SIEMELK Architecture

<p align="center">
 <img alt="SIEMELK Logo" src="images/siemelk-arch.png">
</p>

## SIEMELK Features
✔️ Open Search for Elasticsearch + Kibana + Logstash + Filebeat

✔️ Host and Network Threat Hunting (sysmon + wazuh)

✔️ Embeded IDPS Service

✔️ Netflow support 

✔️ Alerting

✔️ Reporting

✔️ Anomaly Detection

✔️ Cyber Threat Intelligence 

✔️ Incident Response Integration 

✔️ Observables Analyzer 

✔️ Network Scanning module (Web-map)

✔️ Cluster Management

✔️ SOAR Operations

✔️ The SIEM module supports:
- Fortinet (Fortigate, Fortiweb)
- Sophos (Sophos, Cyberoam)
- Cisco (Routers, Switches, ASA, FTD, FMC)
- Linux (security events, FIM)
- Windows (Sysmon, Security events)
- Netflow
- Suricata (IDSTower + 1 year free license)
- Host security analysis - Wazuh
- Login bruteforce attack detection
- MITRE ATT&CK tactics and techniques
- Portsecurity, ARP inspection, DHCP snooping

----
## How to Install?
  - 2nd: [Download OVA package](https://github.com/Mozart4242/SIEMELK/#download)
  - 3rd: Deploy OVA package on your Virtual machine platform (Recommended: VMware ESXI, Workstation, Vsphere)
  - 4th: Power on the VM
  - 5th: Login as:
    - **user: siemelk**
    - **password: siemelk**
  - 6th: Run this command:
    - **"sudo bash setup.sh"**
  - 7th: You are ready to go, happy hunting.
    - **https://ip**
  
  ---------

# Stack
The minimum requierments to deploy the stack:

- 32GB of RAM + 4GB extra (Linux and services)
- 16 Cores of CPU is Good to go.

## How to choose your stack?
your stack resources depends on many factors like :
- how many hosts do you want to monitor?
- how many Endpoints you have?
- how much EPS (Event Per Second) the SIEM should handle?

This table will help you to decide:

| RAM     | CPU    |  DISK | EPS| Entire Need| Stack|
| --------| ------ |-------|----|------------|-----|
|32GB|12|1TB|3K-5K| 40GB RAM| Free|
|48GB|16|2TB|5K-10K|56GB RAM|Paid|
|64GB|24|2TB+|10K+|72GB RAM|paid|

⚠️ **NOTE: The Netflow module requiers a very good performance of your machine. (SSD Disks are recommended)**

------

## Pricing
**SIEMELK** is free to download and use, but if you need the 100% power of SIEMELK for your SOC, then consider the table below:

|Feature/Edition|Free|Enterprise|
|-------|----|----------|
|Platform: |VM|VM|
|Endpoints: |1-200|Up to 1K|
|EPS:|5K|Up to 100K|
|Base SIEM: | ✅| ✅|
|Reports: | ✅| ✅|
|Host Intrusion Detection: | ✅| ✅|
|Cluster Management: | ✅|✅ |
|Anomaly Detection:| ✅| ✅|
|Alerting: |✅ |✅ |
|Network Scanning Module: |❌ | ✅|
|Network Intrusion Detection: |❌ |✅ |
|Upgradeable: | ❌|✅|
|Kubernetes Scalable: |❌ | ✅|
|Threat Intelligence: |❌ | ✅|
|Incident Response: | ❌| ✅|
|SOAR: | ❌| ✅|
|Observability Analyzer: | ❌| ✅|

------
# license?
✔️ To benefit the full functionality of SIEMELK

✔️ To get technical support

## How to order?
✔️ To get the last updates and special price, contact me: certeach@gmail.com

## Architecture Design
✔️ We provide network architecture design and consulting for both **IT** and **OT (SCADA)**, networks.

✔️ We can help you to build your SOC (Securtiy Operations Center) based on the lastest methods available.

---------


# Download
Download The OVA template and deploy it to your VMware infrastructure.
|Release|Size|Package|
|-------|----|-------|
SIEMELK-v1.0|36 GB| ova|
[Part-01]()|4GB||
[Part-02]()|4GB||
[Part-03]()|4GB||
[Part-04]()|4GB||
[Part-05]()|4GB||
[Part-06]()|4GB||
[Part-07]()|4GB||
[Part-08]()|4GB||
[Part-09]()|4GB||

---------

## To Do
- Adding ability to upload your configuration files from web
- Adding ability to add replicas to your Elasticsearch form web
- Adding Message Queuing – Kafka

## Contribution
If you see any bug or have something to improve SIEMELK please file an issue.
