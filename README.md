# Incident Response Playbooks

![NIST](https://img.shields.io/badge/Framework-NIST%20SP%20800--61-blue)
![Playbooks](https://img.shields.io/badge/Playbooks-5-green)

A library of structured Incident Response playbooks authored following the NIST SP 800-61 Rev. 2 framework, covering five high-priority attack scenarios common in enterprise SOC environments.

## Playbooks

| #  | Scenario                                                  | Phases Covered                                |
| -- | --------------------------------------------------------- | --------------------------------------------- |
| 1  | [Ransomware](playbooks/01-ransomware.md)                  | Detection, Containment, Eradication, Recovery |
| 2  | [Phishing](playbooks/02-phishing.md)                      | Detection, Containment, Eradication, Recovery |
| 3  | [Insider Threat](playbooks/03-insider-threat.md)          | Detection, Containment, Eradication, Recovery |
| 4  | [Credential Stuffing](playbooks/04-credential-stuffing.md)| Detection, Containment, Eradication, Recovery |
| 5  | [DDoS](playbooks/05-ddos.md)                              | Detection, Containment, Eradication, Recovery |

## Escalation Matrix

See [escalation-matrix.md](escalation-matrix.md) for tier definitions, SLAs, and contacts.

## Framework

All playbooks follow NIST SP 800-61 Rev. 2 four-phase methodology:

**Detection & Analysis → Containment → Eradication → Recovery**

## Usage

These playbooks are designed to be used as:

- Operational runbooks during active incidents
- Training material for new SOC analysts
- Documentation artifacts for compliance and audit purposes

## Repository Structure

```
ir-playbooks/
├── README.md
├── escalation-matrix.md
├── playbooks/
│   ├── 01-ransomware.md
│   ├── 02-phishing.md
│   ├── 03-insider-threat.md
│   ├── 04-credential-stuffing.md
│   └── 05-ddos.md
└── templates/
    └── playbook-template.md
```

## References

- [NIST SP 800-61 Rev. 2 - Computer Security Incident Handling Guide](https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final)
