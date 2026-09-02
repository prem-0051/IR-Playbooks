# Incident Escalation Matrix

**Version:** 1.0 | **Owner:** SOC Lead | **Last Updated:** 2026-07-14

---

## Internal Escalation Tiers

| Tier | Role | Trigger | Contact Method | SLA |
| ------ | ------ | --------- | ---------------- | ----- |
| T1 | SOC Analyst | Any alert | ITSM ticket | 15 min |
| T2 | SOC Lead / Senior Analyst | Severity High or Critical | Phone + Ticket | 30 min |
| T3 | Security Manager | Multiple systems affected (&gt;5 hosts) | Phone | 1 hour |
| T4 | CISO | Data breach suspected / Business-impacting incident | Phone + Email | 2 hours |
| T5 | Legal / DPO | PII/regulated data exposure | Phone | 4 hours |
| T6 | Executive Team | Critical infrastructure impact / Regulatory notification required | Phone | Same day |

---

## External Escalation

| Party | Trigger | Contact | SLA |
| ------- | --------- | --------- | ----- |
| ISP / Upstream Provider | DDoS / volumetric attack &gt;1Gbps | ISP abuse/NOC line | Immediate |
| CDN Provider (Cloudflare/Akamai) | DDoS mitigation required | Support portal + phone | 15 min |
| Law Enforcement | Criminal activity suspected (data theft, sabotage, nation-state) | Local cybercrime unit / FBI IC3 | Within 24 hrs |
| CERT/CISA | Nation-state or critical infrastructure targeting | us-cert.gov / <report@cisa.dhs.gov> | Within 4 hrs |
| Cyber Insurance | Potential claim event / Ransomware with business impact | Policy number on file / Hotline | Within 24 hrs |
| Threat Intelligence Partners | Confirmed APT activity / Industry-wide campaign | TI platform / ISAC | Within 4 hrs |

---

## Severity Classification Quick Reference

| Severity | Definition | Examples |
| ---------- | ------------ | ---------- |
| **Critical** | Active exploitation; widespread impact; data exfiltration confirmed | Ransomware on 10+ hosts; confirmed data breach; active insider theft |
| **High** | Confirmed malicious activity; limited scope; potential for spread | Single host ransomware; successful phishing with credential compromise |
| **Medium** | Suspicious activity; no confirmed compromise; policy violation | Failed phishing attempts; port scanning; policy violations |
| **Low** | No malicious intent; informational; minimal risk | Spam emails; false positive alerts; routine security events |

---

## Communication Requirements

| Incident Severity | Notification Required | Documentation |
| ------------------- | ---------------------- | --------------- |
| Critical | Immediate phone call to T4+; war room activation | Ticket + Email summary + Post-incident report |
| High | Phone call to T2+ within 30 min | Ticket + Email confirmation |
| Medium | ITSM ticket update; daily shift handover | Ticket updates |
| Low | ITSM ticket only | Standard ticket closure |

---

## Revision History

| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 1.0 | 2026-07-14 | Initial release | SOC Team |
