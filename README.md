
# Introduction to Elasticsearch and Kibana for SIEM


Elasticsearch and Kibana are key components of the Elastic Stack, designed for effective Security Information and Event Management (SIEM). Elasticsearch is a high-speed search and analytics engine that can handle large volumes of data in real time, while Kibana offers a user-friendly interface for visualizing and analyzing this data through customizable dashboards.
# <img width="852" alt="Screenshot 2024-09-06 173500" src="https://github.com/user-attachments/assets/79d21f30-510d-42ba-b876-d99e6ab78111">
#
🔍 **Project Overview**

In this project, I deployed a full-scale honeynet in Google Cloud Platform (GCP) using the ELK Stack (Elasticsearch, Logstash, Kibana). The honeynet involved exposing a Linux VM to the internet to simulate a vulnerable server and capture real attacker behavior.

![20250521_1306_Log Analysis Workflow_remix_01jvt0b92dfs68hk41t1rfenn3](https://github.com/user-attachments/assets/3290a17b-baf7-4408-a868-ddc6100b43ca)



#
**Key features include:**

- Deployment of ELK Stack for log analysis.<details><summary>Click here</summary>
Here’s a step-by-step guide to setting up Elasticsearch with Kibana on a VM in the Google Cloud Platform (GCP). This setup uses a Compute Engine VM to host both Elasticsearch and Kibana for lab or testing purposes.

  **🔧 Prerequisites**
    - Google Cloud account
    - Billing enabled
    - Basic familiarity with Linux command line.
    - Create VM Instance <details><summary>Click here</summary>
  
  

  Click "Create Instance".

  Set the following:

  Name: elastic-kibana

  Region/Zone: Choose closest to you

  Machine Type: e2-medium or better

  Boot Disk:

  OS: Ubuntu 22.04 LTS

  Size: 20GB (or more if needed)

Firewall: ✅ Allow HTTP and ✅ Allow HTTPS

Click Create.
- Integration with VirusTotal and AbuseIPDB for IOC enrichment.

- MITRE ATT&CK mapping of adversary behaviors.
  
- Analysis and visualization of brute-force attempts, suspicious commands, and attacker infrastructure.
  
Here’s a step-by-step guide to setting up Elasticsearch and Kibana as a SIEM system on Ubuntu and I will be using Vultr as a cloud service provider:
