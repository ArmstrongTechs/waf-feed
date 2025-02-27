# 🚀 WAF Feeds - IP Blacklist

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Last Update](https://img.shields.io/github/last-commit/ArmstrongTechs/waf-feed)](https://github.com/ArmstrongTechs/waf-feed)
[![GitHub Repo stars](https://img.shields.io/github/stars/ArmstrongTechs/waf-feed?style=social)](https://github.com/ArmstrongTechs/waf-feed)

A constantly updated list of **malicious IP addresses** for Web Application Firewall (WAF) configurations.

---

## 📖 About

This repository contains a list of **blacklisted IP addresses** known for malicious activities such as:
- 🔥 **Brute-force attacks**
- 🕵️‍♂️ **DDoS & Botnet activities**
- 🎭 **Spamming & Phishing**
- 🚨 **Scanning & Exploitation attempts**

---

## 📂 Repository Structure

| File             | Description                                        |
|------------------|----------------------------------------------------|
| `waf-feeds.txt`  | A list of blacklisted IPs updated frequently.     |
| `LICENSE`        | The MIT License for usage terms.                   |
| `README.md`      | Documentation and usage instructions.              |

---

## 📥 How to Use

### 🔹 1. Download the latest blacklist
You can manually fetch the latest **IP blacklist** using:

```bash
wget -O waf-feeds.txt https://raw.githubusercontent.com/ArmstrongTechs/waf-feed/main/waf-feeds.txt
