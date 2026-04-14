# azure-vm-monitoring-project
Deployed a Linux VM on Azure with NSG-based SSH hardening, configured Nginx web server, set up Azure Monitor with CPU alerts and Log Analytics workspace — verified live log ingestion using KQL Heartbeat queries.

1)Project Title and Overview
Deployed a Linux VM on Microsoft Azure with network security hardening,
web server configuration, and centralized monitoring using Azure Monitor
and Log Analytics.

2)Architecture
Ubuntu VM → NSG (SSH restricted to my IP) → Nginx Web Server
                    ↓
             Azure Monitor → CPU Alert → Email Notification
                    ↓
          Log Analytics Workspace → KQL Heartbeat Query
          
3)Services Used
Azure Virtual Machines
Network Security Groups
Azure Monitor & Alerts
Log Analytics Workspace
KQL (Kusto Query Language)  

4) Screenshots
![VM Overview](VM%20Overview.png)
![NSG Rules](NSG%20Rules.png)
![Nginx Running](Nginx%20Running.png)
![High CPU Alert](High%20CPU%20Alert.png)
![Log Analytics](Log%20Analytics.png)

5) Key Learnings
- Configured NSG rules to restrict SSH access to my IP only
- Deployed and configured Nginx on Ubuntu 24.04
- Set up CPU-based alert rules with email notifications
- Queried live VM logs using KQL in Log Analytics

