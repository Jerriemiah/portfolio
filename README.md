# Jeremiah Inyiama

### IT & Network Support Specialist | AWS Certified | Linux, Networking & Automation

- I support business-critical users, systems, and network infrastructure across retail and managed-service environments. My work focuses on troubleshooting connectivity and endpoint issues, maintaining LAN infrastructure, improving documentation, and building hands-on projects in Linux networking, AWS, Docker, and deployment automation.
- I am currently targeting **IT Support, Network Support, Systems Support, Junior Cloud Support, and Junior DevOps** roles.
- [Email](mailto:Inyiamajeremiah@gmail.com) | [LinkedIn](https://www.linkedin.com/in/jerriemiah/) | [GitHub](https://github.com/Jerriemiah) | [Download CV](#)

---

## Selected Impact

- **4+ years** supporting users, endpoints, business applications, and network infrastructure across IT support and managed-service environments.
- Resolved **250+ technical support tickets** involving connectivity, operating systems, devices, and user-account issues.
- Supported IT operations across **three branch locations**, including POS systems, Microsoft Dynamics 365, LAN infrastructure, Cisco switching, and ISP coordination.
- AWS Solutions Architect Associate and AWS Cloud Practitioner certified.
- Built hands-on projects covering Linux networking, VPC-style isolation, Docker/NGINX deployment, blue/green deployments, and monitoring.

> **Note:** Metrics and scope should only remain here if they are accurate and defensible in an interview.

---

## How to Read This Portfolio

- **For IT Support / Service Desk roles:** Start with [Professional Experience](#professional-experience) and [IT Support & Systems Projects](#it-support--systems-projects).
- **For Network Support / NOC roles:** Start with [Networking Experience & Evidence](#networking-experience--evidence) and [Featured Projects](#featured-projects).
- **For Cloud / DevOps roles:** Start with [Featured Projects](#featured-projects), [Certifications](#certifications), and [Cloud & Infrastructure Projects](#cloud--infrastructure-projects).
- **For technical detail:** Open any project repository to review its README, configuration files, diagrams, and validation notes.

---

## Featured Projects

### 1. `vpcctl` — Linux-Based VPC Networking Lab
**Focus:** Linux networking, routing, NAT, firewall rules, subnet isolation, and cloud-networking fundamentals.  
Built a hands-on lab that recreates core VPC networking concepts using Linux namespaces, virtual Ethernet pairs, bridges, routing tables, `iptables`, and NAT.

**What I built**
- Created isolated Linux network namespaces to represent separate VPC subnets.
- Configured virtual Ethernet pairs, bridges, IP addressing, and routing between network segments.
- Implemented firewall rules and NAT to control traffic flow between environments.
- Tested connectivity, routing paths, and isolation between subnets.

**Why it matters**  
This project demonstrates that I understand the networking concepts behind cloud VPCs rather than only using managed cloud services.

**Technologies:** Linux, iproute2, network namespaces, veth, bridges, iptables, NAT, Bash.  
**Repository:** [View project](https://github.com/Jerriemiah/vpcctl/blob/main/README.md)

---

### 2. Blue/Green Deployment with NGINX and Docker
**Focus:** Deployment automation, high availability, reverse proxying, observability, and failover.  
Designed and implemented a blue/green deployment workflow for a containerized application using Docker, NGINX, and Bash-based automation.

**What I built**
- Containerized the application using Docker and Docker Compose.
- Configured NGINX as a reverse proxy and traffic-switching layer.
- Created a repeatable deployment workflow for releasing new application versions.
- Implemented health checks, logging, and basic monitoring to validate deployments.
- Tested failover by switching traffic between blue and green environments.

**Outcome**
- Reduced deployment risk by enabling traffic to remain available while a new version was validated.
- Improved ability to roll back quickly if a deployment introduced an issue.

**Technologies:** Docker, Docker Compose, NGINX, Bash, Linux, Git, GitHub.  
**Repository:** [View project](https://github.com/Jerriemiah/hng-stage2-bluegreen/blob/main/README.md)

---

### 3. Multi-Site Office Network Expansion
**Focus:** LAN infrastructure, structured cabling, Cisco switching, wireless coverage, and connectivity reliability.  
Supported the expansion and maintenance of office network infrastructure across multiple locations.

**What I did**
- Supported structured cabling and network-device installation during office expansion work.
- Installed and configured routers, switches, access points, desktops, and printers.
- Assisted with VLAN configuration, IP addressing, and LAN troubleshooting.
- Coordinated with ISPs and vendors to restore or maintain site connectivity.
- Documented network assets, connectivity issues, and support procedures.

**Outcome**
- Helped extend reliable network connectivity to new office areas.
- Improved documentation and consistency of network support procedures.

**Technologies:** Cisco switches, VLANs, IP addressing, routers, access points, structured cabling, LAN troubleshooting.  
**Repository / documentation:** [View project](https://github.com/Jerriemiah/network-optimization/blob/main/README.md)

> Replace "Outcome" details with only results you can personally explain and defend.

---

## Professional Experience

### IT Support Specialist — SPAR Nigeria, Novare Mall, Abuja  
**December 2025 – Present | Abuja, Nigeria**
- Provide day-to-day IT support for POS systems, end-user devices, and retail equipment, including label printers and Mettler Toledo scales, across store and warehouse locations.
- Support Microsoft Dynamics 365 and other store-critical business applications used for daily retail operations.
- Maintain and troubleshoot LAN infrastructure, including Cisco switches, VLANs, IP addressing, connectivity issues, and network-device faults.
- Coordinate with ISPs and vendors to diagnose, escalate, and resolve connectivity outages affecting business operations.
- Support employee onboarding by configuring user accounts, email access, permissions, and endpoint access.
- Maintain IT asset inventory and document recurring issues, support procedures, and infrastructure changes.
- [Add metric if available: Supported approximately X users / Y devices / Z sites.]

---

### IT Support & Network Technician — VAS Technologies Ltd  
**January 2023 – January 2025 | Abuja, Nigeria**
- Resolved **250+ technical support tickets** covering connectivity issues, operating-system faults, endpoint devices, printers, and user-account access.
- Installed, configured, and maintained routers, switches, access points, desktops, printers, and basic LAN infrastructure for client environments.
- Supported structured cabling and network-device installation during office expansion projects.
- Performed connectivity diagnostics, cable testing, device configuration, and escalation to ISPs or senior engineers where required.
- Documented support activities, network assets, and recurring technical issues to improve knowledge sharing and issue resolution.
- [Add metric if available: Supported X client sites / Y users / Z network devices.]

---

### IT Support Intern — VAS Technologies Ltd  
**July 2022 – December 2022 | Abuja, Nigeria**
- Assisted with workstation setup, imaging, cable management, and software installation.
- Supported router, printer, and basic network configurations under supervision.
- Logged recurring issues to identify common failure patterns.
- Participated in upgrade and maintenance activities and documented device setups.

---

## Networking Experience & Evidence

### What I Work With
- LAN design, installation, troubleshooting, and maintenance
- Cisco switch administration and VLAN support
- IP addressing, subnetting, routing, and connectivity diagnostics
- Router, access-point, printer, and endpoint network configuration
- ISP coordination, outage escalation, and vendor follow-up
- Structured cabling and office-network expansion support
- Network documentation, asset tracking, and support runbooks

### Typical Troubleshooting Workflow
1. Confirm the scope of the issue: single user, device, VLAN, site, or ISP.
2. Check physical connectivity, device status, IP configuration, and network reachability.
3. Use tools such as `ping`, `tracert`, `ipconfig`, DNS checks, ARP checks, and switch-port verification where appropriate.
4. Isolate whether the issue is endpoint, LAN, wireless, firewall, DNS, DHCP, or ISP-related.
5. Escalate to the ISP, vendor, or senior engineer with clear symptoms, diagnostics, and impact.
6. Document the resolution and update asset or network records.

### Networking Project Evidence
- **Enterprise Office Network Expansion**: Supported fiber connectivity, enterprise switching, routing, and large-scale wireless infrastructure across a newly constructed building.
- **[Project name]**: [Short description of what you configured, tested, or documented.]

> Add a network topology diagram here if possible. Remove public IPs, passwords, internal hostnames, and client-identifying details.

---

## Technical Skills

### IT Support & Systems
- **Advanced:** Windows 10/11 administration, Microsoft 365, Active Directory, user onboarding, account and permission management, hardware/software troubleshooting, ticketing and escalation.
- **Proficient:** Freshdesk, Google Workspace, remote-support tools, IT asset inventory, documentation, printer and peripheral support.
- **Experience:** POS systems, Microsoft Dynamics 365, retail hardware, label printers, Mettler Toledo scales.

### Networking
- **Proficient:** LAN troubleshooting, Wi-Fi troubleshooting, IP addressing, subnetting fundamentals, VLAN concepts, Cisco switch support, router and access-point installation.
- **Working knowledge:** Firewall fundamentals, VPN troubleshooting, DNS, DHCP, NAT, network documentation, ISP escalation.
- **Hands-on lab work:** Linux bridges, virtual Ethernet pairs, network namespaces, routing, iptables, NAT, and VPC-style subnet isolation.

### Cloud & Automation
- **Certified knowledge:** AWS EC2, IAM, S3, CloudWatch, VPC concepts, availability, security groups, and core AWS architecture principles.
- **Hands-on:** Linux, Bash scripting, Docker, Docker Compose, NGINX, Git, GitHub, basic deployment automation.
- **Currently developing:** Terraform, CI/CD, infrastructure as code, monitoring, and production-grade AWS architecture.

### Tools & Platforms
`Windows` • `Microsoft 365` • `Active Directory` • `Freshdesk` • `Google Workspace` • `Cisco` • `Linux` • `Bash` • `Docker` • `NGINX` • `Git` • `GitHub` • `AWS`

---

## Certifications
- [**AWS Certified Solutions Architect – Associate**](https://www.credly.com/badges/f38cf166-b571-447e-924f-ea544381333a/public_url) — Amazon Web Services
- [**AWS Certified Cloud Practitioner**](https://www.credly.com/badges/22f4e75d-bdf8-45f6-aeef-0c6161bb4b48/public_url) — Amazon Web Services
- [**Google IT Support Professional Certificate**](https://coursera.org/share/9fdbdbd298a49e4ed20075fbb66b4c99) — Google / Coursera

---

## Cloud & Infrastructure Projects

- ### Linux Virtual Private Cloud (VPC) Simulation — `vpcctl`
  **Business problem / objective**  
  Cloud networking concepts such as VPCs, subnets, routing, NAT, and isolation are often abstracted by providers, making it difficult to understand how they work internally.
  **What I built**  
  - Created a custom CLI tool (`vpcctl`) to recreate VPC behavior from first principles.
  - Implemented multiple VPCs, subnet isolation, optional peering, firewall rules, and lifecycle cleanup using Linux network namespaces.
  **Architecture**  
  Simulated separate VPC environments locally using virtual Ethernet pairs, bridges, and routing tables.
  **Key technical decisions**  
  - Used native Linux kernel primitives (`iproute2`, `iptables`) to closely mirror cloud networking data paths without proprietary software dependencies.
  **Validation**  
  - Successfully tested packet routing and isolation rules between distinct namespaces.
  **Limitations / improvements**  
  - Expanding multi-node simulation capabilities across separate physical hosts.
  **Technologies**  `Linux` • `Bash` • `Python` • `Git`  
  **Repository**  [View project](https://github.com/Jerriemiah/vpcctl/blob/main/README.md)

- ### Automated Deployment Bash Script
  **Business problem / objective**  
  Manual server setup and application deployment were repetitive, error-prone, and difficult to reproduce reliably.
  **What I built**  
  - Developed a single executable Bash script to automate remote environment preparation, Dockerized application deployment, NGINX reverse proxy configuration, validation, logging, and safe re-runs.
  **Architecture**  
  Script-driven deployment containerized on target Linux hosts with NGINX handling upstream reverse proxy mapping.
  **Key technical decisions**  
  - Designed idempotent script behavior to ensure safe re-execution without breaking existing configurations.
  **Validation**  
  - Validated clean deployments and automated error logging during test runs.
  **Technologies**  `Bash` • `Docker` • `NGINX` • `Git`  
  **Repository**  [View project](https://github.com/Jerriemiah/hng-stage1-devops-deploy/blob/main/README.md)

---

## IT Support & Systems Projects

- ### IT Infrastructure & System Configuration Overhaul
  **Business problem / objective**  
  Inconsistent workstation and peripheral setups led to recurring support issues, performance degradation, and downtime.
  **What I did**  
  - Supported structured setup and configuration of desktops, printers, and network devices, with emphasis on standardization, repeatable installation steps, and clear documentation.
  **Outcome**  
  - Improved system reliability, reduced repeat configuration issues, and strengthened operational consistency through standardized processes.
  **Technologies**  `System Administration` • `Troubleshooting` • `Documentation`  
  **Repository**  [View project](https://github.com/Jerriemiah/it-infrastructure-overhaul/blob/main/README.md)

- ### Customer Support & Managed Network Service Improvement
  **Business problem / objective**  
  Manual incident logging and inconsistent escalation processes led to slow response times and limited visibility for managed network support operations.
  **What I did**  
  - Implemented Freshdesk as a centralized ticketing system, introduced ticket categorization and prioritization, automated responses for common issues, and defined clear escalation workflows for critical incidents.
  **Outcome**  
  - Reduced average response time by approximately **40%**, improved communication with supported sites during outages, and increased overall support efficiency.
  **Technologies**  `Freshdesk` • `IT Support Operations` • `Incident Management`  
  **Repository**  [View project](https://github.com/Jerriemiah/managed-network-support-process-improvement/blob/main/README.md)

---

## Current Focus
I am strengthening my cloud and infrastructure engineering skills through hands-on projects in:
- AWS networking, EC2, IAM, S3, CloudWatch, and VPC design
- Terraform and infrastructure as code
- CI/CD pipelines using GitHub Actions
- Linux server administration and troubleshooting
- Docker-based application deployment
- Network documentation, monitoring, and incident-response workflows

---

## Contact
[![Gmail](https://skillicons.dev/icons?i=gmail)](mailto:Inyiamajeremiah@gmail.com) [![LinkedIn](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/jerriemiah/) [![GitHub](https://skillicons.dev/icons?i=github)](https://github.com/Jerriemiah)
