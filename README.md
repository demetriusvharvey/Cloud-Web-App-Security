# 🛡️ Cloud Web App Security Project

This project demonstrates how to deploy and secure a public-facing web application on [AWS or Azure], applying core cloud security principles including network hardening, IAM controls, logging, and monitoring.

---

## 🔧 Tech Stack

- Platform: [AWS EC2 / Azure App Service]
- App: [Flask / Node.js / Static HTML]
- Tools: Security Groups / NSGs, IAM, CloudTrail / Azure Monitor, GuardDuty / Defender, WAF, CloudWatch / Log Analytics

---

## 📌 Project Goals

- ✅ Deploy a basic public web app
- ✅ Harden cloud infrastructure
- ✅ Implement IAM with least privilege
- ✅ Enable monitoring and alerting
- ✅ Document end-to-end setup

---

## 🚀 Deployment Overview

### 1. Launch Instance
- [ ] Deployed [Amazon Linux 2 / Ubuntu] VM
- [ ] Installed web app (e.g., Flask)

### 2. Network Hardening
- [ ] Allowed ports: 80/443 only
- [ ] Locked SSH to specific IPs
- [ ] Applied WAF (basic ruleset)

### 3. IAM & Permissions
- [ ] Created instance role with minimal S3 permissions
- [ ] Verified no hardcoded credentials in app

### 4. Logging & Monitoring
- [ ] Enabled CloudTrail / Azure Activity Log
- [ ] Enabled GuardDuty / Defender
- [ ] Configured CloudWatch Logs & Alarms

---

## 🔐 Security Controls Summary

| Category            | Control                        | Configured? |
|---------------------|--------------------------------|-------------|
| Network             | Security Group / NSG           | ✅           |
| Identity & Access   | IAM Role, Least Privilege      | ✅           |
| App Security        | WAF + HTTPS                    | ✅/🔲        |
| Monitoring & Alerts | CloudTrail + GuardDuty         | ✅           |

---

## 📸 Screenshots

> Include screenshots of:
- Deployed app
- Security group settings
- IAM role config
- Log/alert dashboards

---

## 🧠 Lessons Learned

- [Example] Always start with least privilege IAM and expand only when needed.
- [Example] GuardDuty catches brute-force SSH attempts even in test setups.

---

## 📈 Next Steps

- [ ] Add HTTPS (via ACM / TLS cert)
- [ ] Add CI/CD security checks
- [ ] Auto-remediation using Lambda or Azure Automation

---

## 📚 References

- [AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)
- [Azure Security Best Practices](https://learn.microsoft.com/en-us/azure/security/fundamentals/)

