# MS-102 - Microsoft 365 Administrator - Visual Study Guide

> Concept-only study aid. No exam questions reproduced. Source PDF (if any) stays local + gitignored.

**Skills outline:** https://learn.microsoft.com/en-us/credentials/certifications/exams/ms-102/

## Master mind map

```mermaid
mindmap
  root((MS-102))
    Deploy and Manage a Microsoft 365 Tenant
      Plan and configure a Microsoft 365 tenant region, subscription, cus...
      Manage users, licenses, groups, contacts, mailboxes
      Manage roles and role groups
      Configure organizational settings release channels, branding, custo...
      Manage tenant-level health Service Health, Message Center, Adoption...
    Implement and Manage Entra Identity and Access
      Plan and implement identity sync with Entra Connect / Cloud Sync
      Manage external collaboration B2B, Cross-tenant access settings
      Implement and manage authentication MFA, passwordless, CA, Identity...
      Implement and manage Conditional Access for M365 workloads
      Investigate sign-in / audit logs
    Manage Security and Threats with Microsoft Defender XDR
      Implement and manage Defender for Office 365 anti-phish, anti-malwa...
      Implement and manage Defender for Endpoint onboarding, ASR, EDR, AV
      Implement and manage Defender for Identity sensors on DCs, identity...
      Implement and manage Defender for Cloud Apps CASB, app discovery, c...
      Investigate threats with Defender XDR incidents, hunting, attack di...
    Manage Compliance with Microsoft Purview
      Manage sensitivity labels publish, auto-label
      Manage retention labels and policies
      Manage DLP for M365 services and Endpoint DLP
      Manage Insider Risk Management policies
      Manage eDiscovery Standard / Premium and audit Std/Prem
```

## Domain map

```mermaid
flowchart LR
    Master["MS-102 Master Index"]
    D01["Deploy and Manage a Microsoft 365 Tenant"]
    Master --> D01
    D02["Implement and Manage Microsoft Entra Identity and Access"]
    Master --> D02
    D03["Manage Security and Threats with Defender XDR"]
    Master --> D03
    D04["Implement and Manage Microsoft 365 Compliance"]
    Master --> D04
```

## Domain weights

```mermaid
pie showData
    title MS-102 domain weights
    "Deploy and Manage a Microsoft 365 Tenant" : 27
    "Implement and Manage Microsoft Entra Identity and Access" : 18
    "Manage Security and Threats with Defender XDR" : 33
    "Implement and Manage Microsoft 365 Compliance" : 22
```

> Click a slice / legend label to jump to that chapter.

## Recommended study order

```mermaid
gantt
    title Suggested study plan
    dateFormat X
    axisFormat Day %d
    section Plan
    Deploy and Manage a Microsoft 365 Tenant :t1, 0, 2d
    Implement and Manage Microsoft Entra Identity and Access :t2, after t1, 2d
    Manage Security and Threats with Defender XDR :t3, after t2, 2d
    Implement and Manage Microsoft 365 Compliance :t4, after t3, 2d
```

---

**Next:** open [01-m365-tenant.md](01-m365-tenant.md)

<!-- TODO: fill remaining sections via Copilot chat. Target structure mirrors c:\az305\study-guide\00-MASTER-INDEX.md. -->
