# Public Wi-Fi Security Awareness Study 

This repository contains all the materials related to my project on user behavior and security awareness when connecting to public Wi-Fi networks. 

## Repository Structure 
- analysis.ipynb: 
  Jupyter notebook coontaining all the data analysis, visualizations, and statistical tests performed on the collected data. 
- wifi_ap_config/:
  Folder containing the configuration files used to set up the Raspberry Pi as a mobile Wi-Fi access point.
  It includes:
  - Hostapd configuration (for Wi-Fi access point)
  - Dnsmasq configuration (for DHCP and DNS)
  - Nodogsplash configuration (for captive portal setup)
- data/:
  Folder containing the collected datasets:
  - Survey responses
  - Network activity (DNS queries and connection times)
 
## Project Overview 
The goal of this project was to evaluate to what extent users are aware of the potential cybersecurity risks when connecting to a free public network. 
The methodology involved: 
- Setting up a mobile Wi-Fi access point using a Raspberry Pi
- Forcing users to answer a brief survey before granting internet access
- Collecting anonymized DNS and connection metadata during their sessions
- Analyzing the correlation between selft-reported awareness and actual online behavior 

