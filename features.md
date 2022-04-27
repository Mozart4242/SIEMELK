## Built On Open Source
SIEMonster is built on the best of Open Source tools with extra functionality, integration stability and correlation providing enriching data from the SIEM.
Some of these tools include.

### Open Distro
Open Distro for Elasticsearch provides a powerful, easy-to-use event monitoring and alerting system, enabling you to monitor your data and send notifications automatically to your stakeholders. With an intuitive Kibana interface and powerful API, it is easy to set up and manage alerts. Build specific alert conditions using Elasticsearch’s query and scripting capabilities. Alerts help teams reduce response times for operational and security events.

<p align="center">
 <img alt="" src="opendistro.png">
</p>

-----

### The Hive
TheHive is utilized within the SIEMonster platform as an incident response/case management system. It is meshed with Alerting, MISP, OpenCTI, Patrowl and Cortex to automate the process of incident creation. To make life simpler for SOCs, CSIRTs and CERTs, all information pertaining to a security incident is presented for review. Whilst weighing up and excluding false positives, the SOC team are given an indication of next steps to take.

<p align="center">
 <img alt="SIEMELK Logo" src="hive.png">
</p>

-----

### MITRE ATT&CK
MITRE ATT&CK is a globally accessible knowledge base of adversary tactics and techniques based on real-world observations. The ATT&CK knowledge base is used as a foundation for the development of specific threat models and methodologies in the private sector, in government, and in the cybersecurity product and service community.

<p align="center">
 <img alt="" src="mitre.png">
</p>

------
### OpenCTI
OpenCTI is an open source platform allowing organizations to manage their cyber threat intelligence knowledge and observables. It has been created in order to structure, store, organize and visualize technical and non-technical information about cyber threats.


The structuration of the data is performed using a knowledge schema based on the STIX2 standards. It has been designed as a modern web application including a GraphQL API and an UX oriented frontend. Also, OpenCTI is integrated with MISP, TheHive and MITRE ATT&CK within the SIEMonster platform as well as having a connector for CVE information.

<p align="center">
 <img alt="SIEMELK Logo" src="opencti.jpg">
</p>

------

### Message Queuing – Kafka
Apache Kafka is a publish/subscribe message queuing system that is utilized within SIEMonster not only for its scalability but also for the following:

1- Provides durable, fast and fault tolerant message streaming for handling real time data feeds.

2- Compatible with Apache Nifi and the Elastic Beats family agents.

3- Enables custom configuration per endpoint group by using topic declarations.

4- Improving data governance and guaranteed delivery.

5- Options for in flight stream data extraction and new stream creation dependent on specific triggers.

6- Ability to set data retention periods per use case in case of upstream processing back pressure.


Incoming events are stored initially in Apache Kafka before being processed in Nifi and then sent to Elasticsearch. This provides a buffer in case of bursts in activity while also providing an endpoint by topic management system with options for real time alert stream creation.

<p align="center">
 <img alt="" src="kafka.png">
</p>

-----

### Wazuh
Wazuh is a free and open source platform for threat detection, security monitoring, incident response and regulatory compliance. It can be used to monitor endpoints, cloud services and containers, and to aggregate and analyze data from external sources. Wazuh is used to collect, aggregate, index and analyze security data, helping organizations detect intrusions, threats and behavioral anomalies.

<p align="center">
 <img alt="" src="wazuh.png">
</p>

-----

### Suricata
Suricata is an open source threat detection engine that was developed by the Open Information Security Foundation (OISF). Suricata can act as an intrusion detection system (IDS), and intrusion prevention system (IPS), or be used for network security monitoring. It was developed alongside the community to help simplify security processes. As a free and robust tool, Suricata monitors network traffic using an extensive rule set and signature language. Suricata also features Lua scripting support to monitor more complex threats.



SIEMonster provides a Suricata pipeline that performs packet capture and analysis on the local network interface, acting as a host-based IDS. The resultant data is then sent to Kafka before being ingested by Elasticsearch. The commercial SIEMonster releases extend these capabilities in the form of network and cloud tabs and multi-network interface monitoring.

 
Alerts can be easily configured for signature matches and there is also a dashboard provided for further IDS analysis.

 <p align="center">
 <img alt="" src="suricata.png">
</p>
