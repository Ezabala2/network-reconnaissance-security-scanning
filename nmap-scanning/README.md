# Nmap TCP, UDP & Service Detection

## Overview
This assignment examined Nmap options and applied TCP and UDP scanning to a Metasploitable2 target in an authorized lab.

## Tools
- Nmap
- Parrot OS
- Metasploitable2 (intentionally vulnerable training VM)

## Work performed
- Reviewed `-h` (help), `-V` (Nmap version), `-6` (IPv6), `-sU` (UDP), and `-e` (interface selection).
- Verified target reachability using `ping`.
- Scanned all TCP ports and identified service versions using `sudo nmap -sV -p- <LAB_TARGET>`.
- Scanned UDP ports 1–111 with version detection using `sudo nmap -sU -sV -p 1-111 <LAB_TARGET>`.

## Documented findings
- Lowest open TCP port: **21/tcp (FTP)**.
- Highest open TCP port reported: **54460/tcp**.
- Lowest confirmed open UDP port: **53/udp (DNS)**.
- UDP port 111 reported **rpcbind version 2**.
- PostgreSQL version reported as **8.3.0–8.3.7**.

## Evidence
Screenshots are in `screenshots/` and retain the order of the original submitted assignment.

## Scope
Only scan systems for which you have explicit authorization. `<LAB_TARGET>` is a placeholder for a training VM address.
