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

