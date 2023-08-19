# Blue Team Lab
This project contains documentation to create a blue team lab consisting of several security perimeter components. The security perimeter devices used include SIEM, NIDS, and HIDS. Additionally, this lab will provide a detailed explanation of the installation process for each security perimeter device. All installed security perimeter devices are based on open-source technology.

## Blue Team Topology
I'm used 3 Server to create blue team lab. First is dummy server farm that installed elastic agent for HIDS, second suricata server for NIDS, and last for ELK server. Security Analyst can see all of activity on server farm and network using ELK dashboard.
![alt text](https://github.com/Ngatz/blueteamlab/blob/main/Blue%20Team%20Lab%20Topology.png)
