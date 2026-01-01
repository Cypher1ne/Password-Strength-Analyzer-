# Password Policy Evaluation & Authentication Risk Analysis Tool

![Security Tool](https://img.shields.io/badge/Security-Defensive%20Analysis-blue)
![Pure Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-yellow)

## 🔒 Overview

A pure HTML/CSS/JavaScript defensive security tool that evaluates password strength and maps weaknesses to real-world attack techniques. No frameworks, no build process - just open and use.

**Live Demo:** [https://YOUR-USERNAME.github.io/password-security-analyzer/](https://YOUR-USERNAME.github.io/password-security-analyzer/)

## 🎯 Purpose

Demonstrates understanding of:
- Password entropy calculation and complexity analysis
- Time-to-crack estimation using modern GPU attack speeds
- Mapping weaknesses to MITRE ATT&CK techniques (T1110.x)
- Risk assessment aligned with NIST SP 800-63B standards

**Use Case:** Security awareness training, password policy development, authentication risk assessment for SOC operations.

## 🚀 Features

### Core Analysis
- **Entropy Calculation:** Measures password randomness based on character diversity
- **Pattern Detection:** Identifies sequential characters, repeated patterns, common passwords
- **Attack Simulation:** Estimates crack time for CPU and GPU-based attacks (configurable)
- **Dark Mode:** Professional UI with light/dark theme toggle

### Attack Technique Mapping
Maps password weaknesses to specific threats:
- **Brute Force Attack** (MITRE T1110.001) - Systematic enumeration
- **Dictionary Attack** (MITRE T1110.002) - Common password exploitation
- **Rule-Based Cracking** (MITRE T1110.002) - Pattern-aware algorithms
- **Credential Stuffing** (MITRE T1110.004) - Breach database reuse

### Risk Classification
- Critical / High / Medium / Low authentication risk levels
- Business impact explanation (account takeover, privilege escalation, lateral movement)
- Actionable security recommendations (MFA, passphrases, password managers)

## 🛡️ Security & Privacy

- **100% Client-Side:** All analysis happens in your browser
- **No Data Transmission:** Passwords never leave your device
- **No Dependencies:** No external libraries or API calls
- **No Logging:** No analytics, tracking, or data storage
- **Open Source:** Full code transparency in single HTML file

## 🏗️ Technical Stack

- **Language:** Pure Vanilla JavaScript (ES6+)
- **Styling:** Inline CSS with CSS Variables
- **Architecture:** Single-page application (SPA)
- **Deployment:** GitHub Pages (static hosting)

**No build tools, no npm, no frameworks - just HTML/CSS/JS**

## 📚 Standards Alignment

This tool follows security best practices from:
- **NIST SP 800-63B:** Digital Identity Guidelines (Password Recommendations)
- **OWASP:** Authentication Cheat Sheet
- **MITRE ATT&CK:** Credential Access tactics (T1110 family)

## 🚦 How to Use

1. Enter a test password in the analysis field
2. Review the real-time risk assessment and entropy calculation
3. Examine which MITRE ATT&CK techniques apply
4. Adjust GPU attack speed slider to model different threat actors
5. Read actionable recommendations for improvement

**Note:** Use test passwords only. Never enter real credentials.

## 💻 Local Development
```bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/password-security-analyzer.git

# Open in browser
# Just double-click index.html - no installation needed!
```

**That's it!** No dependencies to install, no build process to run.

## 📖 Educational Context

This project demonstrates understanding of:
- **Authentication Security:** Password hygiene as primary defense against credential attacks
- **Attack Methodologies:** GPU acceleration, rainbow tables, dictionary attacks
- **Defensive Analysis:** Risk assessment, entropy calculation, pattern detection
- **Security Frameworks:** NIST, OWASP, MITRE ATT&CK
- **SOC Operations:** Threat modeling, risk classification, incident impact analysis

## ⚠️ Disclaimer

**FOR EDUCATIONAL AND DEFENSIVE SECURITY PURPOSES ONLY**

This tool is designed for:
- ✅ Security awareness and training
- ✅ Password policy evaluation
- ✅ Understanding authentication risks
- ✅ SOC analyst skill development

NOT intended for:
- ❌ Offensive security operations
- ❌ Unauthorized access attempts
- ❌ Malicious password cracking
- ❌ Penetration testing without authorization

Always follow responsible disclosure and ethical security practices.

## 📄 License

MIT License - Free to use for educational purposes

## 👤 Author

**[Your Name]**
- GitHub: [@cypher1ne](https://github.com/Cypher1ne)
- LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/soumitra-patra-a72102368/)
- Portfolio: [Your Portfolio](https://cypher1ne.github.io/Portfolio/)

**Aspiring Cybersecurity Analyst | SOC Operations | Defensive Security**

## 🙏 Acknowledgments

- NIST for password guidelines (SP 800-63B)
- OWASP for authentication best practices
- MITRE for the ATT&CK framework
- Cybersecurity community for ongoing research

---

**⭐ If this tool helped you understand authentication security, please star the repository!**
