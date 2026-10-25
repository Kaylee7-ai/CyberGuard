# CyberGuard - Autonomous AI Security Agent

## Problem: Fragmented Intelligence
Security teams have logs in one place, threat intelligence in another. They can't join data fast enough. Hackers get in.

## Solution: Zetaris AI Data Fabric
CyberGuard uses Zetaris to create a virtual unified layer over fragmented CSVs WITHOUT moving data (Zero ETL). 
It federates website logs + hacker threat feeds in real-time.

## How it Works
1. **Unified Layer**: Zetaris connects to website-logs.csv and hacker-list.csv as virtual tables
2. **Federated Query**: Agent runs `SELECT * WHERE fail_count > 20 AND threat_level='Critical'` across both
3. **Autonomous Action**: If match, auto-blocks IP and generates incident report with explainability

## Demo
IP 185.220.101.47 tried 25 failed logins. Zetaris layer joins with threat feed -> Identified as Tor Exit Node - Critical - Russia - Risk 95. Action: Blocked.

## Tech Stack
Python, Pandas (simulating Zetaris federated engine), GenAI.Works deployment

## Founder: Kaylee7-ai (Accra, Ghana)
Built for GenAI.Works & Zetaris Challenge: Agentic AI & Data Fabric
