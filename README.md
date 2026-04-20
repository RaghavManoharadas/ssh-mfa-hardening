# SSH Hardening with Multi-Factor Authentication (MFA)

## 📄 Full Technical Report
👉 [View Report](./reports/ssh-mfa-hardening.pdf)

## Overview
This project focuses on securing SSH access by implementing multi-factor authentication (MFA) and hardening configurations to reduce attack surface and prevent unauthorized access.

## 🔐 Key Implementations
- Configured SSH server securely
- Disabled root login
- Disabled password-based authentication
- Enabled public key authentication
- Integrated Google Authenticator for MFA
- Modified PAM configuration for OTP enforcement

## 🔍 Security Improvements
- Eliminated brute-force attack vectors
- Strengthened authentication using multi-factor verification
- Reduced exposure to automated scanning attacks
- Enforced secure access policies

## ⚠️ Security Risks Addressed
- Weak password-based authentication
- Unauthorized root access
- Credential brute-force attacks
- SSH service exposure on default configurations

## 🛡️ Mitigation Strategies
- Use key-based authentication instead of passwords
- Enforce MFA for all remote access
- Change default SSH port
- Disable unnecessary SSH features (X11, TCP forwarding)
- Monitor login attempts and logs

## 🛠️ Tools & Technologies
- Ubuntu Server
- OpenSSH
- Google Authenticator (PAM module)
- Linux CLI

## 📌 Conclusion
This project demonstrates how proper SSH configuration and MFA integration significantly enhance system security and protect against common attack vectors.
