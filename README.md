![GitHub stars](https://img.shields.io/github/stars/shi88ihs//torblock?style=social)
![GitHub forks](https://img.shields.io/github/forks/shi88ihs//torblock?style=social)
![GitHub issues](https://img.shields.io/github/issues/shi88ihs//torblock)
![GitHub last commit](https://img.shields.io/github/last-commit/shi88ihs//torblock)
![ShellCheck](https://img.shields.io/badge/ShellCheck-passing-success)

# VPS-Tor-Exit-Nodes-NTFtables-Blocking-Script-
Tor Exit Nodes Blocking Script for Securing VPS' &amp; Web Infrstucture

# 🛡️ TorBlock - Automated Tor Exit Node Blocker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Shell Script](https://img.shields.io/badge/Shell_Script-121011?logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![nftables](https://img.shields.io/badge/nftables-required-blue)](https://netfilter.org/projects/nftables/)

🛡️ TorBlock - Production-grade Tor exit node blocker for Linux servers

A production-ready bash script that automatically blocks all known Tor exit nodes using nftables firewall rules. Designed for Linux servers that need to restrict anonymous Tor traffic while maintaining simplicity and reliability.

Secure your server from anonymous Tor traffic with this lightweight, 
zero-dependency bash script. Uses nftables for efficient IP filtering. 
Perfect for web servers, APIs, and services requiring authenticated access.

⚡ Blocks 1000+ Tor nodes in seconds

🔒 Production-tested and battle-hardened

📊 Detailed logging and verification

🚀 Easy automation with cron/systemd


## 🎯 Features

- **Automated IP Blocking**: Loads and blocks 1000+ Tor exit node IPs automatically
- **nftables Integration**: Uses modern Linux firewall framework with efficient set-based filtering
- **Robust Error Handling**: Validates each IP and provides detailed status reporting
- **Zero Dependencies**: Pure bash script with only nftables required
- **Production Ready**: Includes logging, verification, and easy removal
- **Idempotent**: Safe to run multiple times - cleans and recreates rules

## 📋 Prerequisites

- Linux system with kernel 3.13+ (for nftables support)
- nftables installed (`nft` command available)
- Root/sudo privileges
- Bash 4.0 or higher


