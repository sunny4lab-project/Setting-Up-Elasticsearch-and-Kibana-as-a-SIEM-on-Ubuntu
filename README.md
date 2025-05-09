
# Introduction to Elasticsearch and Kibana for SIEM


Elasticsearch and Kibana are key components of the Elastic Stack, designed for effective Security Information and Event Management (SIEM). Elasticsearch is a high-speed search and analytics engine that can handle large volumes of data in real-time, while Kibana offers a user-friendly interface for visualizing and analyzing this data through customizable dashboards.
# <img width="852" alt="Screenshot 2024-09-06 173500" src="https://github.com/user-attachments/assets/79d21f30-510d-42ba-b876-d99e6ab78111">
#
🔍 **Project Overview**

In this project, I deployed a full-scale honeynet in Google Cloud Platform (GCP) using the ELK Stack (Elasticsearch, Logstash, Kibana). The honeynet involved exposing a Linux VM to the internet to simulate a vulnerable server and capture real attacker behavior.

#
**Key features include:**

- Deployment of ELK Stack for log analysis.

- Integration with VirusTotal and AbuseIPDB for IOC enrichment.

- MITRE ATT&CK mapping of adversary behaviors.
  
- Analysis and visualization of brute-force attempts, suspicious commands, and attacker infrastructure.
  
Here’s a step-by-step guide to setting up Elasticsearch and Kibana as a SIEM system on Ubuntu and I will be using Vultr as a cloud service provider:
