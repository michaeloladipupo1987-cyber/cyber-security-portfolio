# Secure Business Network Deployment

## Project Overview

This project involved designing and configuring a secure business network using Cisco Packet Tracer.

The scenario was based on a business expanding its network infrastructure and required the configuration of network services, wireless connectivity and basic security controls.

## Project Objectives

The main objectives were to:

- Configure the network topology
- Configure router interfaces
- Configure DHCP
- Configure DNS
- Configure email services
- Configure wireless networking
- Implement WPA2 security
- Configure secure remote access using SSH
- Apply basic network security hardening
- Test network connectivity

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- IPv4
- DHCP
- DNS
- SSH
- Wireless networking
- WPA2-PSK

## Network Configuration

The network included two main network segments:

- Office 1: `192.168.1.0/24`
- Office 2: `192.168.2.0/24`

The router interfaces were configured to provide connectivity between the networks.

## DHCP Configuration

A DHCP server was configured for Office 2.

The DHCP configuration included:

- Server IP: `192.168.2.1`
- Subnet Mask: `255.255.255.0`
- Default Gateway: `192.168.1.10`
- DNS Server: `192.168.1.10`
- Starting Address: `192.168.2.50`
- Maximum Users: `100`

The client devices were tested to confirm that they could obtain IP addresses automatically.

## Wireless Security

The wireless network was configured with:

**SSID:** `MainOffice`

**Security:** WPA2-PSK

Wireless clients successfully connected and received IP addresses.

## Email Configuration

An email server was configured using the domain:

`ts.com`

The server was configured to provide email services to network users.

## Secure Remote Access

SSH was configured to provide secure remote management of the network device.

This provided encrypted remote access instead of using the less secure Telnet protocol.

## Troubleshooting

During the project, I encountered DHCP addressing issues with wireless clients.

I investigated the network configuration and identified an incorrect IP network assignment.

The addressing was corrected so that the wireless clients could communicate with the correct network and obtain IP addresses successfully.

## Testing

Network connectivity was tested using tools such as:

```text
ping
