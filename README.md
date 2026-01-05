# 🪟 Windows Enterprise Administration

This project is a comprehensive, hands-on lab series focused on **Windows Enterprise Administration**. It demonstrates the setup, configuration, and management of a Windows domain environment using **Active Directory**, **Group Policy**, **PowerShell**, and **enterprise endpoint security tools**.

The labs progress from foundational domain setup to advanced endpoint automation, monitoring, and security logging—mirroring real-world enterprise IT and SOC environments.

---

## 🧪 Lab Overview

By completing this project, the following enterprise administration tasks were successfully implemented:

- Configured a Windows Server as a Domain Controller
- Deployed and managed Active Directory users, groups, and policies
- Enrolled and administered domain-joined workstations
- Enforced security and endpoint policies using Group Policy
- Implemented centralized logging, monitoring, and automation
- Enabled secure remote administration using PowerShell

---

## 🔹 Lab 1: Domain Controller Setup & Active Directory Deployment

### Objectives
- Set up a Windows Server as a Domain Controller
- Install Active Directory Domain Services (AD DS)
- Promote the server to a Domain Controller
- Verify domain and forest configuration

### Description
In this lab, a Windows Server was configured to act as a Domain Controller in an enterprise environment. This involved installing the AD DS role, creating a new domain, and verifying the server’s ability to centrally manage users, devices, and policies. This foundational setup enables centralized authentication, authorization, and policy enforcement across the domain.

---

## 🔹 Lab 2: Active Directory Administration (Users & Admins)

### Objectives
- Open and navigate the Active Directory Administrative Center (ADAC)
- Modify the Administrator account password policy
- Create a standard domain user
- Create a domain administrator account

### Description
This lab focused on Active Directory user management. Administrative tools were used to modify password policies and create both standard and privileged accounts within the domain. This establishes proper role separation between regular users and administrators.

---

## 🔹 Lab 3: Workstation Enrollment & RDP Access Validation

### Objectives
- Enroll a workstation into the domain
- Verify successful domain membership
- Test RDP connectivity as a Domain Admin and standard user

### Description
A Windows workstation was enrolled into the domain and verified as a domain-joined system. Remote Desktop Protocol (RDP) access was tested from the Domain Controller to ensure that Domain Admins had access while standard users were restricted appropriately.

---

## 🔹 Lab 4: Organizational Units, Groups, and Group Policy Objects

### Objectives
- Understand Organizational Units (OUs)
- Review existing Group Policy Objects (GPOs)
- Create an RDP Users security group
- Apply a GPO to grant RDP access
- Verify RDP access for authorized users

### Description
This lab introduced Organizational Units and Group Policy Objects as tools for structuring and securing enterprise environments. A custom security group was created for RDP access, and a GPO was applied to ensure that only authorized users could remotely access domain-joined systems.

---

## 🔹 Lab 5: Endpoint Security Policies & PowerShell Logging

### Objectives
- Test PowerShell script execution permissions
- Restrict PowerShell script execution using GPOs
- Enable PowerShell logging
- Verify policy enforcement
- View PowerShell logs remotely from the DC

### Description
Endpoint security controls were implemented using Group Policy to restrict PowerShell script execution for standard users. Logging policies were enabled to capture script execution attempts, allowing administrators to monitor and audit PowerShell activity across the domain.

---

## 🔹 Lab 6: File Shares, Network Discovery & Shadow Copies

### Objectives
- Create and configure a shared folder
- Enable Network Discovery via Group Policy
- Enable Shadow Copies for file recovery
- Test file access and recovery permissions

### Description
A shared folder was created and made accessible to domain users. Network Discovery was enforced via Group Policy, and Shadow Copies were enabled to allow file recovery. A standard user deleted a file, and a Domain Admin successfully restored it, demonstrating enterprise-grade data protection.

---

## 🔹 Lab 7: Remote Monitoring & Management with PowerShell

### Objectives
- Enable remote PowerShell management using GPOs
- Monitor and manage a remote workstation
- Retrieve system information and running processes
- Restart services and systems remotely
- Export PowerShell execution logs to HTML

### Description
This lab demonstrated remote system administration using PowerShell. Required policies were configured, allowing the Domain Admin to execute monitoring and management commands remotely, collect logs, and export them for reporting and analysis.

---

## 🔹 Lab 8: Endpoint Automation with Build Scripts (Chocolatey)

### Objectives
- Configure Chocolatey remotely
- Install software using PowerShell automation
- Deploy multiple applications via inline scripts
- Verify endpoint usability as a standard user

### Description
Chocolatey was configured on a remote workstation to automate software installation. Applications such as Notepad++, 7-Zip, Sysinternals Suite, and Adobe Acrobat Reader were deployed remotely. The standard user verified access to installed tools, including Autoruns.

---

## 🔹 Lab 9: Sysmon Deployment & Enhanced Logging

### Objectives
- Configure Sysmon remotely
- Generate and analyze Sysmon log entries
- Inspect enhanced endpoint telemetry

### Description
Sysmon was deployed using a pre-configured configuration file to enable enhanced system logging. User activity generated log entries, which were then inspected and analyzed from the Domain Controller to demonstrate advanced endpoint visibility and security monitoring.

---

## 🧠 Skills Demonstrated

- Windows Server Administration
- Active Directory & Group Policy
- PowerShell Automation & Remoting
- Endpoint Security & Hardening
- Centralized Logging & Monitoring
- Enterprise IT & SOC Readiness

---

## 📌 Conclusion

This **Windows Enterprise Administration** project demonstrates a complete, enterprise-style Windows domain environment—from initial domain setup to advanced endpoint security and automation. The labs reflect real-world administrative, security, and monitoring tasks commonly performed by **IT administrators, system engineers, and SOC analysts**.

