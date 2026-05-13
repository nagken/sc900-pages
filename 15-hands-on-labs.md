# Hands-On Labs - SC-900

> Free-tier or trial labs you can run end-to-end in 30-60 minutes.

### 1. Tour the Microsoft Entra admin center

Sign in to entra.microsoft.com with a free Microsoft 365 dev tenant (developer.microsoft.com/microsoft-365/dev-program). Add a user, create a group, assign a role, set MFA registration policy.

### 2. Create a Conditional Access policy

In Entra admin center -> Protection -> Conditional Access. Create a policy that requires MFA for all users when signing in to All cloud apps. Use 'Report-only' first, then enable.

### 3. Build your first Sentinel workspace

In a free trial Azure subscription, create a Log Analytics workspace + enable Microsoft Sentinel. Add the Microsoft Entra ID connector. Run a KQL query: SigninLogs | take 10.

### 4. Defender for Cloud secure score

Open portal.azure.com -> Defender for Cloud. Look at recommendations on a free-tier resource, fix one (enable MFA on a privileged role), watch the secure score change.

### 5. Apply a sensitivity label

In purview.microsoft.com -> Information Protection, publish a label policy. Open Word for the web, apply the label, observe the watermark and protection.


---

[Master Index](00-MASTER-INDEX.md)
