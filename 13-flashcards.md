# Flashcards - SC-900

> Click any card to reveal the answer. Use the Domain pager bottom-right to switch between exam areas.

<section class="fc-section" data-fc-title="Security Compliance and Identity Concepts">
<h2>1 - Security Compliance and Identity Concepts</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">What are the three Zero Trust principles?</div><div class="fc-a">Verify explicitly, use least-privilege access, assume breach.</div></div>

<div class="flashcard"><div class="fc-q">Authentication vs authorization?</div><div class="fc-a">AuthN proves identity; AuthZ grants permissions to that identity.</div></div>

<div class="flashcard"><div class="fc-q">Symmetric vs asymmetric encryption?</div><div class="fc-a">Symmetric uses one shared key (fast, AES); asymmetric uses a public/private key pair (slow, RSA, used for key exchange/signing).</div></div>

<div class="flashcard"><div class="fc-q">What is hashing used for?</div><div class="fc-a">Integrity. A one-way function that detects tampering; not reversible.</div></div>

<div class="flashcard"><div class="fc-q">What is federation?</div><div class="fc-a">An agreement that lets identities issued by one IdP be trusted by another (SAML, WS-Fed, OIDC).</div></div>

<div class="flashcard"><div class="fc-q">In the cloud shared-responsibility model, who owns identities and data?</div><div class="fc-a">The customer always owns identities, data, devices, and accounts (across IaaS, PaaS, SaaS).</div></div>

<div class="flashcard"><div class="fc-q">What is a non-repudiation control?</div><div class="fc-a">A digital signature - proves origin and integrity so the signer cannot deny sending it.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Microsoft Entra Capabilities">
<h2>2 - Microsoft Entra Capabilities</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Which Entra license is required for Identity Protection and PIM?</div><div class="fc-a">Entra ID P2 (or Microsoft 365 E5).</div></div>

<div class="flashcard"><div class="fc-q">What is a managed identity?</div><div class="fc-a">An automatically-managed identity in Entra ID for Azure resources - no secrets to rotate.</div></div>

<div class="flashcard"><div class="fc-q">Difference between system-assigned and user-assigned MI?</div><div class="fc-a">System-assigned: 1:1 with the resource, deleted with it. User-assigned: standalone, can be shared across resources.</div></div>

<div class="flashcard"><div class="fc-q">Three hybrid identity authentication methods?</div><div class="fc-a">Password Hash Sync (PHS), Pass-through Auth (PTA), Federation (AD FS).</div></div>

<div class="flashcard"><div class="fc-q">What does Conditional Access evaluate?</div><div class="fc-a">Signals (user, device, location, app, risk) and applies access controls (block, MFA, compliant device, etc.).</div></div>

<div class="flashcard"><div class="fc-q">What is PIM used for?</div><div class="fc-a">Just-in-time, time-bound, approval-required activation of privileged Entra and Azure roles.</div></div>

<div class="flashcard"><div class="fc-q">Entra External ID replaces what?</div><div class="fc-a">Azure AD B2C for new customer-identity scenarios.</div></div>

<div class="flashcard"><div class="fc-q">What is Entra Verified ID?</div><div class="fc-a">A decentralized identity service for issuing/verifying digitally signed credentials (W3C standard).</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Microsoft Security Solutions">
<h2>3 - Microsoft Security Solutions</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Which workloads make up Defender XDR?</div><div class="fc-a">Defender for Endpoint, Office 365, Identity, Cloud Apps (+ Vulnerability Mgmt).</div></div>

<div class="flashcard"><div class="fc-q">What is the difference between Defender for Cloud and Defender XDR?</div><div class="fc-a">Defender for Cloud secures Azure/AWS/GCP resources; Defender XDR secures M365 endpoints, email, identities, SaaS apps.</div></div>

<div class="flashcard"><div class="fc-q">What does CSPM stand for?</div><div class="fc-a">Cloud Security Posture Management - posture, recommendations, secure score.</div></div>

<div class="flashcard"><div class="fc-q">What is Microsoft Sentinel?</div><div class="fc-a">A cloud-native SIEM and SOAR built on Log Analytics + Logic Apps.</div></div>

<div class="flashcard"><div class="fc-q">What language do you query Sentinel with?</div><div class="fc-a">KQL (Kusto Query Language).</div></div>

<div class="flashcard"><div class="fc-q">Difference between NSG and Azure Firewall?</div><div class="fc-a">NSG = stateless ACLs at subnet/NIC; Firewall = stateful, FQDN, threat intel, central.</div></div>

<div class="flashcard"><div class="fc-q">What does Azure Bastion provide?</div><div class="fc-a">Browser-based RDP/SSH to VMs over TLS without public IPs on the VMs.</div></div>

<div class="flashcard"><div class="fc-q">Premium tier of Key Vault adds what?</div><div class="fc-a">FIPS 140-2 Level 3 HSM-backed keys.</div></div>

</div>
</section>
<section class="fc-section" data-fc-title="Microsoft Compliance Solutions">
<h2>4 - Microsoft Compliance Solutions</h2>

<div class="flashcard-grid">

<div class="flashcard"><div class="fc-q">Where do you manage Microsoft compliance?</div><div class="fc-a">purview.microsoft.com (Microsoft Purview compliance portal).</div></div>

<div class="flashcard"><div class="fc-q">What is Compliance Manager?</div><div class="fc-a">A risk-assessment tool that scores your tenant against templates (HIPAA, GDPR, ISO, etc.).</div></div>

<div class="flashcard"><div class="fc-q">Sensitivity labels protect what?</div><div class="fc-a">Documents and emails - via encryption, watermarks, header/footer, access rights.</div></div>

<div class="flashcard"><div class="fc-q">Two main types of DLP locations?</div><div class="fc-a">M365 services (Exchange/SharePoint/OneDrive/Teams) and Endpoints (Endpoint DLP).</div></div>

<div class="flashcard"><div class="fc-q">What is the difference between retention labels and policies?</div><div class="fc-a">Labels are applied to items; policies apply broad container-level retention.</div></div>

<div class="flashcard"><div class="fc-q">Insider Risk Management triggers on what?</div><div class="fc-a">Indicators like resignation date + data exfil, downloads, file deletions.</div></div>

<div class="flashcard"><div class="fc-q">Premium eDiscovery adds what?</div><div class="fc-a">Review sets, predictive coding/ML, advanced holds, custodian management.</div></div>

<div class="flashcard"><div class="fc-q">Service Trust Portal contains?</div><div class="fc-a">Microsoft's third-party audit reports (SOC 2, ISO, FedRAMP, etc.).</div></div>

</div>
</section>

---

[Master Index](00-MASTER-INDEX.md)
