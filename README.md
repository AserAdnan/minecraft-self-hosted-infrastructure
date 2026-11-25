# minecraft-self-hosted-infrastructure

# Minecraft Self-Hosted Infrastructure

A self-hosted Minecraft server infrastructure built and
managed on personal hardware.

## Project Overview

This project explores self-hosting, virtualization,
Linux server administration, and private networking.

The goal was to deploy a remotely accessible Minecraft
server for players located in different regions.

## Technology Stack

- Host OS: Windows 11
- Virtualization: Oracle VirtualBox
- Guest OS: Ubuntu Server
- Server Management: PufferPanel
- Game Server: Minecraft 1.21.11
- Mod Loader: Fabric
- Private Networking: Tailscale

## Architecture

Windows 11 Host
    |
    +-- VirtualBox
          |
          +-- Ubuntu Server VM
                |
                +-- PufferPanel
                |
                +-- Minecraft Fabric Server
                |
                +-- Tailscale Connectivity

## Key Implementations

- Deployed an Ubuntu Server virtual machine.
- Configured a Minecraft Fabric server.
- Set up server management using PufferPanel.
- Established private connectivity using Tailscale.
- Tested remote connectivity between the host and VM.

## Challenges & Troubleshooting

- Virtual machine networking.
- IPv4 and IPv6 connectivity.
- Remote access across different networks.
- Server deployment and configuration.

## Project Status

Operational.

## Future Improvements

- Performance monitoring.
- Network latency measurements.
- Automated backups.
- Resource utilization monitoring.
- Improved access management.

## Disclaimer

This project is for educational and personal use.
