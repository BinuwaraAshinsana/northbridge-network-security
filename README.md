# Northbridge Savings & Finance Network Security Upgrade

## Module
IE3122 - Network Security

## Project
Network Security Upgrade for Northbridge Savings & Finance

## Overview
This project designs and evaluates a secure network architecture for
Northbridge Savings & Finance.

The solution includes:
- Network segmentation using VLANs
- Secure branch connectivity
- Access Control Lists
- Firewall architecture
- AAA
- VPN
- IDS/IPS
- Centralized logging
- Network hardening

## Network Structure
- Head Office
- Branch 1
- Branch 2
- ISP/WAN simulation
- Staff VLAN
- Server VLAN
- Admin VLAN
- Guest VLAN
- DMZ

## VLANs

| VLAN | Name | Network |
|------|------|---------|
| 10 | STAFF | 10.10.10.0/24 |
| 20 | SERVERS | 10.10.20.0/24 |
| 30 | ADMIN | 10.10.30.0/24 |
| 40 | GUEST | 10.10.40.0/24 |
| 50 | DMZ | 10.10.50.0/24 |

## Branch Networks
- Branch 1: 10.20.10.0/24
- Branch 2: 10.30.10.0/24
