# purple-team-active-directory-lab
Purple Team Active Directory lab for simulating attacks and analyzing detection opportunities
# Purple Team Active Directory Detection Lab

## Overview

A hands-on Purple Team lab built in VirtualBox to understand
Active Directory security, attack paths, Kerberos authentication,
SPNs, and credential-based attacks.

## Lab Environment

- Windows Server 2022 – Domain Controller
- Kali Linux – Security testing machine
- VirtualBox
- Active Directory Domain: purplelab.local
- BloodHound
- Neo4j
- Impacket

## Activities Performed

- Configured a Windows Active Directory domain
- Created domain users and service accounts
- Configured a service account with an MSSQL SPN
- Enumerated Active Directory relationships and attack paths
  using BloodHound
- Performed Kerberos service account enumeration
- Simulated Kerberoasting in the lab environment
- Analyzed security weaknesses and potential attack paths

## Key Concepts Learned

- Active Directory
- Kerberos authentication
- Service Principal Names (SPNs)
- Kerberoasting
- BloodHound
- Attack path analysis
- Purple Team methodology

## Screenshots

Screenshots of the lab setup, BloodHound analysis,
and attack simulation are included in the `screenshots`
directory.

## Disclaimer

This project was performed in an isolated lab environment
for educational and cybersecurity learning purposes.
