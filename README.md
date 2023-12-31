# Blue Team Lab
This project contains documentation to create a blue team lab consisting of several security perimeter components. The security perimeter devices used include SIEM, NIDS, and HIDS. Additionally, this lab will provide a detailed explanation of the installation process for each security perimeter device. All installed security perimeter devices are based on open-source technology.

## Blue Team Topology
I'm used 3 **Virtual Server** to create blue team lab. First is dummy server farm that installed elastic agent for HIDS, second suricata server for NIDS, and last for ELK server. Security Analyst can see all of activity on server farm and network using ELK dashboard.
![alt text](https://github.com/Ngatz/blueteamlab/blob/main/Lab%20Topology.png)

## Blue Team Tools
1. pfSense Community
2. ELK stack (SIEM - Security Information and Event Management)
3. Elastic agent (HIDS - Host Intrusion Detection System)
4. Suricata (NIDS - Network Intrusion Detection System)

## Requirement
### pfSenses Server
1. Ram 4GB
2. 2 Core
3. Storage 20GB

### ELK Server
1. RAM 4GB
2. 2 Core
3. Storage 50GB

### Suricata Server
1. RAM 4GB
2. 2 Core
3. Storage 50GB

### Dummy Server Farm
1. RAM 2GB
2. 2 Core
3. Storage 50GB

## Installation
Detail of installation security perimeter you can read on my [wiki](https://github.com/Ngatz/blueteamlab/wiki/Installation-Lab)
