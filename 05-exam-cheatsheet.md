# SC-900 Exam Decision Reference

> Compressed decision table covering the entire exam. Use 1 day before the test.

| Scenario | Pick | Why |
|---|---|---|
| Need MFA for risky sign-ins only | Conditional Access + Identity Protection (P2) | Risk-based CA |
| Federation vs PHS for hybrid | PHS unless you need on-prem MFA / smartcard at sign-in | PHS is simplest |
| PIM vs RBAC role assignment | PIM for privileged roles (eligible) | JIT, time-bound, approval |
| Defender XDR vs Defender for Cloud | XDR = M365 estate; DfC = cloud workloads | Different scopes |
| Sentinel vs Defender XDR | Sentinel = SIEM (any source); XDR = native MS sources | Often used together |
| Compliance Manager vs Service Trust | Manager = your posture; Trust = Microsoft's posture | Two sides of compliance |
| Sensitivity vs Retention label | Sensitivity = protect now; Retention = keep/delete later | Different lifecycles |
| DLP vs IRM (Insider Risk) | DLP = block known data; IRM = flag suspicious behavior | Rules vs behavior |
| Bastion vs JIT VM Access | Bastion = browser RDP/SSH; JIT = open NSG ports temporarily | Combine for best result |
| Azure Firewall vs WAF | Firewall = network L3-L7; WAF = HTTP-only OWASP rules | Use both |

---

[Master Index](00-MASTER-INDEX.md)
