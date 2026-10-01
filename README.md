# Network Configuration Automation with Ansible and GitLab CI/CD

## Overview

This project focuses on automating the deployment and verification of a
service-provider network using Ansible and GitLab CI/CD.

The network implements MPLS L3VPN services and includes OSPF, MPLS/LDP,
BGP, MP-BGP, VRFs, DHCP, and BGP path control.

## Technologies

- Cisco IOS
- EVE-NG
- Ansible
- GitLab CI/CD
- Linux
- OSPF
- BGP
- MPLS/LDP
- MPLS L3VPN
- Git
- Ansible Lint

## Automation

Ansible is used to automate:

- Interface configuration
- DHCP configuration
- OSPF deployment
- MPLS/LDP deployment
- VRF creation
- CE-PE eBGP
- PE-RR iBGP
- MP-BGP
- BGP path control

## Verification

Automated verification playbooks check:

- OSPF neighbors
- MPLS/LDP neighbors
- BGP sessions
- L3VPN routes
- Network connectivity

## CI/CD Pipeline

The GitLab CI/CD pipeline performs:

1. Validation
2. Network connectivity checks
3. Configuration deployment
4. Automated verification

## Lab Environment

The topology was implemented using EVE-NG and Cisco IOS virtual routers.

## Future Improvements

- Configuration compliance
- Multivendor automation
- Network telemetry
- Security automation
- Automated testing with a dedicated CI environment
