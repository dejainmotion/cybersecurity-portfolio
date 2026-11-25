# Departmental Network, Systems, and Security Setup

**Organization:** ULTA Beauty (Simulated Enterprise Environment)  
**Project Type:** Senior Cybersecurity Capstone  
**Institution:** St. Philip's College  
**Year Completed:** May 2026

## 1. Project Overview

This project involved designing and implementing a simulated enterprise network, systems infrastructure, and security environment for ULTA Beauty.

The objective was to develop a departmental IT environment that supports five business departments through network segmentation, centralized user and computer management, network services, and security policies.

The project consisted of two technical environments:

- **Network Infrastructure:** Designed and configured a departmental network using Cisco Packet Tracer, including routers, switches, VLANs, IP addressing, and connectivity testing.
- **Windows Systems Infrastructure:** Deployed Windows Server 2022 and Windows 11 virtual machines to configure Active Directory Domain Services (AD DS), DNS, DHCP, Group Policy, domain-joined clients, and shared folder permissions.

The project also included security design considerations and a corporate computer and acceptable use policy addressing system access, data protection, password security, and responsible AI usage.

Together, these components demonstrate how enterprise networking, Windows systems administration, and security governance contribute to a more organized and secure business environment.

## 2. Project Objectives

The primary objectives of this project were to:

1. Design a departmental enterprise network consisting of five separate business departments.
2. Configure network segmentation to organize departmental traffic and restrict unauthorized communication between departments.
3. Configure Cisco routers and switches to support departmental connectivity.
4. Implement IP addressing and DHCP services across the departmental network segments.
5. Deploy Windows Server 2022 and configure Active Directory Domain Services.
6. Configure DNS for internal domain name resolution.
7. Deploy Windows 11 client machines and join them to the enterprise domain.
8. Implement Group Policy Objects (GPOs) to establish centralized security and system configurations.
9. Configure shared folders and access permissions.
10. Develop security design documentation and a corporate computer and acceptable use policy, including guidelines for responsible AI usage.
11. Test and document network connectivity, system configurations, and security implementations.

## 3. Network Architecture and Design

The network infrastructure was designed to represent a simulated enterprise environment for ULTA Beauty. The organization was divided into five departments, each assigned a separate network segment to support departmental organization and traffic separation.

### Departmental Network Segmentation

The five departments included:

- Human Resources (HR)
- Finance
- Retail
- Marketing
- Information Technology (IT)

Each department was assigned its own VLAN to logically separate network traffic and support departmental access restrictions.

### Network Design Components

The network topology was designed and configured in Cisco Packet Tracer using:

- Cisco routers
- Cisco switches
- Departmental VLANs
- IP addressing and subnetting
- Inter-network routing
- Wireless network access
- Connectivity testing using ICMP ping

The design focused on departmental segmentation, network communication, and limiting unnecessary access between business departments.

### Network Security Objective

Network segmentation was used to establish logical boundaries between departments. The design included access restrictions intended to prevent unauthorized communication between departmental networks while supporting the organization's operational requirements.

## 4. Network Configuration and Implementation

The departmental network was manually configured in Cisco Packet Tracer to establish separate network segments and enable communication between designated network devices.

### Configuration Tasks

- Created and assigned VLANs for the five business departments.
- Configured switch ports to support departmental VLAN assignments.
- Configured router interfaces and routing to support communication between network segments.
- Assigned IP addresses to network devices and departmental segments.
- Configured wireless network access.
- Implemented network connectivity testing using ICMP ping.
- Tested communication between devices to verify network connectivity and departmental access restrictions.

### Network Configuration Documentation

The project included individual configuration commands for the Cisco network devices used in the topology.

**Supporting evidence:**
- Cisco Packet Tracer network topology
- Router configuration commands
- Switch configuration commands
- IP addressing information
- Network connectivity test results

## 5. Windows Server 2022 Implementation

Windows Server 2022 was deployed in a virtual machine to establish the organization's centralized Windows domain environment.

### Active Directory Domain Services (AD DS)

- Installed and configured Active Directory Domain Services.
- Created the `ultabeauty.local` domain.
- Established a centralized domain environment for managing users and computers.
- Configured domain-related organizational and administrative settings.

### DNS and DHCP Services

- Configured DNS to support internal domain name resolution.
- Configured DHCP to provide IP address assignments to client systems.
- Established the network services needed to support the Windows domain environment.

### Group Policy Management

- Created and linked Group Policy Objects (GPOs).
- Configured centralized policy settings to support organizational security requirements.
- Used Group Policy Management to administer domain-level policy configurations.

### Shared Folders and Permissions

- Configured shared folders for organizational use.
- Established access permissions to support controlled access to shared resources.

**Supporting evidence:**
- Windows Server 2022 virtual machine screenshots
- Active Directory configuration
- DNS and DHCP configuration
- Group Policy Management screenshots
- Shared folder and permission screenshots

## 6. Windows 11 Client Configuration

Windows 11 virtual machines were deployed to represent employee workstations within the ULTA Beauty domain environment.

### Client Configuration Tasks

- Deployed Windows 11 client virtual machines.
- Configured client network settings and IP addressing.
- Connected Windows 11 client machines to the `ultabeauty.local` domain.
- Verified domain membership and client connectivity.
- Used Group Policy tools to examine policy application on the client environment.
- Configured client systems to operate within the organization's centralized Windows environment.

### Domain and Policy Management

Domain-joined client machines provided a way to demonstrate centralized user and computer administration through Active Directory.

Group Policy was used to establish organizational security settings and manage client configurations.

**Supporting evidence:**
- Windows 11 virtual machine screenshots
- Client IP configuration
- Domain membership verification
- Group Policy results
- Client environment testing

## 7. Security Design and Implementation

Security considerations were incorporated throughout the network and Windows systems environments to support the confidentiality, integrity, and availability (CIA) of organizational resources.

### Network Security

- Implemented departmental network segmentation using VLANs.
- Established logical separation between business departments.
- Configured network devices to support controlled communication between network segments.
- Designed the network to reduce unnecessary departmental access.

### Windows Systems Security

- Implemented centralized account and computer management through Active Directory.
- Configured Group Policy Objects to support consistent security settings.
- Established shared folder permissions to control access to organizational resources.
- Incorporated account and access management considerations into the Windows domain environment.

### Security Design Documentation

A separate security design document was developed to identify security devices, technologies, and protection categories relevant to the simulated enterprise environment.

The design addressed organizational protection needs across areas such as:

- Network security
- Wireless security
- Web security
- Email security
- Data protection

### Security Objectives

The overall security approach focused on:
- Restricting unauthorized access.
- Separating departmental resources.
- Supporting centralized security administration.
- Protecting organizational information.
- Reducing risks associated with improper system and network use.

**Supporting evidence:**
- Security design document
- Cisco network configurations
- Windows Server security configurations
- Group Policy screenshots
- Shared folder permission screenshots

## 8. Corporate Computer and Acceptable Use Policy

As part of the project, a corporate computer and acceptable use policy was developed for the simulated ULTA Beauty enterprise environment.

The policy established guidelines for the responsible and secure use of company computers, networks, systems, internet access, and artificial intelligence tools.

### Policy Areas

The policy addressed the following areas:

- **Acceptable Use:** Defined appropriate use of company systems, networks, and technology resources.
- **Prohibited Activities:** Identified unauthorized activities, including password sharing, unauthorized software installation, and attempts to bypass security controls.
- **Password and Account Security:** Established password requirements and account protection responsibilities.
- **Data Protection and Confidentiality:** Addressed the handling and protection of customer, employee, financial, and internal company information.
- **Artificial Intelligence Usage:** Established guidelines for approved AI tools, protecting confidential information, reviewing AI-generated content, and maintaining human oversight.
- **Monitoring and Enforcement:** Outlined organizational monitoring practices and consequences for policy violations.
- **Employee Acknowledgment:** Established expectations for employee understanding and compliance.

### Policy Objectives

The policy was designed to:
- Promote responsible use of organizational technology.
- Protect confidential and sensitive business information.
- Reduce risks associated with unauthorized access and misuse.
- Establish expectations for password and account security.
- Encourage responsible and secure use of AI technologies.

**Supporting evidence:**
- ULTA Corporate Computer & Acceptable Use Policy

## 9. Tools and Technologies

- Cisco Packet Tracer
- Windows Server 2022
- Windows 11
- Virtual Machines
- Active Directory Domain Services (AD DS)
- DNS and DHCP
- Group Policy Management

## 10. Technical Skills Demonstrated

- **Network Administration:** VLANs, IP addressing, subnetting, routing, switching, and network troubleshooting.
- **Windows Systems Administration:** Windows Server 2022, Active Directory, DNS, DHCP, Group Policy, and domain management.
- **Access Control:** Domain administration, departmental segmentation, and shared folder permissions.
- **Cybersecurity:** Network security, security configurations, data protection, and security policy development.
- **Governance:** Acceptable use policies, AI usage guidelines, and security documentation.
