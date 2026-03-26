# James Carter

**CEO & Co-Founder @ Cipher Rescue Chains, LLC**  
*Former: Binance (Global Intelligence) | U.S. Department of the Treasury - FinCEN*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jamescarter-cipher)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/jamescarter_cipher)
[![Website](https://img.shields.io/badge/cipherrescuechains.com-FF6B6B?style=for-the-badge&logo=web&logoColor=white)](https://cipherrescuechains.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jamescarter-cipher)

---

## 📋 About Me

I lead **Cipher Rescue Chains, LLC**, a blockchain intelligence and asset recovery firm dedicated to helping victims of cryptocurrency fraud and theft. My career has been defined by bridging the gap between blockchain technology and financial crime enforcement.

**Core Expertise:**
- 📜 Anti-Money Laundering (AML) & Bank Secrecy Act (BSA) compliance
- 🌐 Global sanctions enforcement and evasion detection
- 🏛️ Regulatory policy development for virtual currency
- 🤝 Public-private partnerships in financial crime investigation
- 🔍 Cryptocurrency exchange intelligence and investigations

---

## 💼 Professional Background (2015–Present)

### Cipher Rescue Chains, LLC (2022 – Present)
**Chief Executive Officer & Co-Founder**

Leading a specialized firm that combines advanced on-chain forensics with global law enforcement partnerships to trace, freeze, and repatriate stolen digital assets. Built the company from inception to a trusted partner for victims and agencies worldwide.

**Key Achievements:**
- Founded company in 2022 with co-founders Daniel Vaughn and Ryan Holt
- Built relationships with 45+ law enforcement agencies globally
- Developed proprietary Helios Tracing Engine with CTO
- Successfully recovered assets for victims across 12 countries

---

### Binance (2019 – 2022)
**Senior Director, Global Intelligence & Investigations**

Led the regional investigations team for the Americas. Coordinated with FBI, DOJ, Secret Service, and international agencies on high-profile cases involving ransomware groups, exchange hacks, and state-sponsored actors.

**Key Achievements:**
- Led investigations resulting in freezing over **$500M in illicit funds**
- Built the regional investigations team from 3 to 25+ personnel
- Established formal intelligence-sharing protocols with 7 federal agencies
- Developed training program for 50+ law enforcement partners on crypto tracing

**Notable Cases:**
- DarkSide ransomware investigation (Colonial Pipeline related)
- REvil ransomware takedown coordination
- Multiple exchange hack investigations
- North Korea (Lazarus Group) sanctions evasion cases

---

### U.S. Department of the Treasury – FinCEN (2015 – 2019)
**Special Advisor, Virtual Currency**

Served as subject matter expert on anti-money laundering compliance for cryptocurrency exchanges. Helped draft key guidance regarding the application of the Bank Secrecy Act to convertible virtual currencies.

**Key Achievements:**
- Co-authored FinCEN Guidance FIN-2015-G001 on cryptocurrency exchanges
- Authored 2019 advisory on ransomware and cryptocurrency
- Represented the United States at FATF Virtual Currency Working Group (2017–2019)
- Developed examination procedures for crypto-focused financial institutions
- Trained 200+ federal and state examiners on virtual currency compliance

---

## 📚 GitHub Repositories

### [sanctions-list-wrapper](https://github.com/jamescarter-cipher/sanctions-list-wrapper)
*Python • MIT License*

A unified Python wrapper for global sanctions lists:
- OFAC SDN List (United States)
- EU Consolidated Sanctions
- UN Security Council Sanctions
- UK HMT Sanctions
- Canadian Consolidated Autonomous Sanctions

```python
from sanctions_checker import SanctionsScanner

scanner = SanctionsScanner()
result = scanner.check_address("0x742d35Cc6634C0532925a3b844Bc9e759cFfC0B4")
print(f"Sanctions match: {result.matches}")
print(f"Risk score: {result.risk_score}")
print(f"List source: {result.source}")
