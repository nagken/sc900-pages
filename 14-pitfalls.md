# Common Pitfalls - SC-900

> Frequent confusions, traps, and "gotchas" that cause wrong answers on the exam.

### Confusing brands (Entra vs Defender vs Purview)

Entra = identity. Defender = security/threat. Purview = data governance + compliance. Memorize the mapping.

### Mixing up Defender XDR and Defender for Cloud

XDR protects M365 (endpoints, email, identities, SaaS). Defender for Cloud protects Azure/AWS/GCP resources. They overlap only via Sentinel ingest.

### Thinking PHS exposes plaintext passwords

PHS uploads a hash of the SHA256 hash of the user's password - not the password itself.

### Forgetting that conditional access requires P1+

Free Entra has no Conditional Access. Identity Protection and PIM need P2.

### Sensitivity labels do NOT auto-classify by default

You must enable auto-labeling and assign trainable classifiers or SITs - and it requires E5 / Compliance E5.


---

[Master Index](00-MASTER-INDEX.md)
