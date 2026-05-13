# SC-900 - Microsoft Security Compliance and Identity Fundamentals - Visual Study Guide

> Concept-only study aid. No exam questions reproduced. Source PDF (if any) stays local + gitignored.

**Skills outline:** https://learn.microsoft.com/en-us/credentials/certifications/exams/sc-900/

## Master mind map

```mermaid
mindmap
  root((SC-900))
    Security Compliance and Identity Concepts
      Define the Zero Trust security model and its guiding principles
      Define defense in depth and the shared responsibility model
      Describe common threats phishing, malware, ransomware, DDoS
      Describe encryption, hashing, and signing at a high level
      Define identity as the new security perimeter
    Microsoft Entra Capabilities
      Describe Microsoft Entra ID formerly Azure AD and its editions
      Describe identity types user, device, service principal, managed id...
      Describe hybrid identity options PHS, PTA, federation
      Describe authentication methods passwords, MFA, passwordless Window...
      Describe Conditional Access, Identity Protection, and PIM
    Microsoft Security Solutions
      Describe Microsoft Defender XDR formerly 365 Defender and its workl...
      Describe Defender for Endpoint, Office 365, Identity, Cloud Apps, a...
      Describe Microsoft Sentinel data connectors, analytics rules, hunti...
      Describe Defender for Cloud secure score, regulatory compliance, wo...
      Describe Azure DDoS Protection, Azure Firewall, Web Application Fir...
    Microsoft Compliance Solutions
      Describe Microsoft Purview compliance portal, data governance
      Describe Compliance Manager and compliance score
      Describe sensitivity labels, DLP, retention labels and policies
      Describe insider risk management, communication compliance, eDiscov...
      Describe Service Trust Portal and Microsoft Privacy principles
```

## Domain map

```mermaid
flowchart LR
    Master["SC-900 Master Index"]
    D01["Security Compliance and Identity Concepts"]
    Master --> D01
    D02["Microsoft Entra Capabilities"]
    Master --> D02
    D03["Microsoft Security Solutions"]
    Master --> D03
    D04["Microsoft Compliance Solutions"]
    Master --> D04
```

## Domain weights

```mermaid
pie showData
    title SC-900 domain weights
    "Security Compliance and Identity Concepts" : 12
    "Microsoft Entra Capabilities" : 28
    "Microsoft Security Solutions" : 38
    "Microsoft Compliance Solutions" : 22
```

> Click a slice / legend label to jump to that chapter.

## Recommended study order

```mermaid
gantt
    title Suggested study plan
    dateFormat X
    axisFormat Day %d
    section Plan
    Security Compliance and Identity Concepts :t1, 0, 1d
    Microsoft Entra Capabilities :t2, after t1, 2d
    Microsoft Security Solutions :t3, after t2, 2d
    Microsoft Compliance Solutions :t4, after t3, 2d
```

---

**Next:** open [01-security-concepts.md](01-security-concepts.md)

<!-- TODO: fill remaining sections via Copilot chat. Target structure mirrors c:\az305\study-guide\00-MASTER-INDEX.md. -->
