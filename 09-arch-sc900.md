# Architectures - SC-900

> Reference architectures you should be able to draw on a whiteboard for the exam.

## Zero Trust signal flow

```mermaid
flowchart LR
    User[User] --> Entra[Entra ID]
    Device[Device] --> Intune[Intune compliance]
    Entra --> CA{Conditional Access}
    Intune --> CA
    Risk[Identity Protection risk] --> CA
    CA -->|allow| App[Cloud app]
    CA -->|MFA| App
    CA -->|block| Deny((Deny))
```

## Defender XDR + Sentinel

```mermaid
flowchart TD
    DfE[Defender for Endpoint] --> XDR[Defender XDR]
    DfO[Defender for Office 365] --> XDR
    DfI[Defender for Identity] --> XDR
    DfCA[Defender for Cloud Apps] --> XDR
    XDR --> Sentinel[Microsoft Sentinel]
    DfC[Defender for Cloud] --> Sentinel
    Other[3rd-party logs] --> Sentinel
    Sentinel --> SOC[SOC analyst]
```


---

[Master Index](00-MASTER-INDEX.md)
