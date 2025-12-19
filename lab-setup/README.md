# Lab Setup

## Domain Controller
- Windows Server 2022
- Static IP: 10.0.0.10
- Roles Installed:
  - Active Directory Domain Services
  - DNS
  - Active Directory Certificate Services
- Domain Name: corp.local

## Users
- john – Standard domain user
- svc_sql – Service account with SPN
- admin1 – Domain Admin account

## Kerberos & ADCS Configuration
- Kerberos pre-authentication disabled for user john
- SPN configured for svc_sql
- Vulnerable ADCS certificate template created (ESC1)
