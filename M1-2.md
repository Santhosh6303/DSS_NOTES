# Host-Level Threats and Vulnerabilities Notes

## Introduction
- Vulnerabilities: Weaknesses allowing system compromise
- Threats: Potential for system damage or compromise

## Types of Vulnerabilities
1. Transient Code: Mobile code executing on remote hosts
   - E.g., Scripts, Applets, ActiveX objects
2. Resident Code: Trusted software with potential vulnerabilities
   - E.g., Installed applications, system software

## Malware

### Trojan Horse
- Disguised as legitimate software (e.g., screensavers, games)
- Creates backdoors, disables security, prepares for DDoS attacks

### Spyware
- Secretly records user actions (e.g., capturing credit card details)
- Examples: SearchSeekFind, ShopAtHomeSelect, Surfairy

### Worms/Viruses
- Self-replicating, infect files with malicious code
- Spread through networks, unlike user-dependent Trojans

## Eavesdropping

### Unauthorized Access to Confidential Data
- By Users:
  - Accessing staged job data in shared folders
  - Exploiting cookies for user information
- By Jobs:
  - Grid jobs accessing sensitive host information (e.g., password files)

### Unauthorized Access to Protected Binaries
- Accessing proprietary algorithms (e.g., insurance rate calculator)
- Exploiting hardcoded credentials in binaries

### Unauthorized Tampering with Computational Results
- Altering results of long-running jobs using intermediate files

## Job Faults
- Untested applications causing system crashes
- Malicious jobs targeting hosts for shutdown/reboot

## Resource Starvation
- Long grid jobs consuming excessive CPU/memory
- Affecting native host applications and interactive desktop use

## Overflow

### Stack-Based Buffer Overflow
- Overwriting variables or return addresses
- Executing arbitrary code by altering function pointers

### Heap-Based Buffer Overflow
- Overflowing dynamically allocated memory
- Corrupting program data structures

## Privilege Escalation

### Horizontal Privilege Escalation
- Assuming peer user identity to access private data

### Vertical Privilege Escalation
- Gaining root/admin privileges for full system control
- Often exploited through buffer overflows

## Injection Attacks

### Shell/PHP Injection
- Exploiting server-side scripting vulnerabilities (PHP, ASP)

### SQL Injection
- Injecting malicious queries through insecure input fields
- Retrieving unauthorized data or manipulating database
