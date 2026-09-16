# Azure Endpoint Management & Zero-Trust IT Operations 

## Project Overview
A practical Microsoft Azure / Microsoft Entra / Microsoft Intune lab demonstrating modern endpoint administration, device compliance, application deployment, endpoint security, Conditional Access, and troubleshooting.

> This project intentionally focuses on modern cloud endpoint management rather than traditional Windows Server / Active Directory infrastructure.

## Architecture

```text
                         Microsoft Entra ID
                    Users / Groups / MFA / RBAC
                               |
                               v
                    +----------------------+
                    |   Microsoft Intune  |
                    |----------------------|
                    | Enrollment           |
                    | Configuration        |
                    | Compliance           |
                    | Applications         |
                    | Endpoint Security    |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Windows 11 Endpoint  |
                    |       WIN11-01       |
                    |----------------------|
                    | Defender             |
                    | Firewall             |
                    | BitLocker            |
                    | Corporate Policies   |
                    +----------+-----------+
                               |
                               v
                    +----------------------+
                    | Conditional Access   |
                    | MFA + Device State   |
                    +----------------------+
```

## Objectives
- Manage Windows endpoints through Microsoft Intune.
- Use Microsoft Entra ID for cloud identity and groups.
- Enroll a Windows endpoint into Intune.
- Apply configuration and compliance policies.
- Deploy a business utility application.
- Configure Defender Antivirus, Firewall, and BitLocker policies.
- Implement MFA and Conditional Access.
- Investigate endpoint and sign-in problems.
- Document incidents like a real IT operations team.

## Lab Components

| Component | Example |
|---|---|
| Identity | Microsoft Entra ID |
| Endpoint management | Microsoft Intune |
| Endpoint | Windows 11 / WIN11-01 |
| Security | Microsoft Defender, Firewall, BitLocker |
| Access control | Conditional Access + MFA |
| Application management | Intune app deployment |
| Documentation | Incident records |

## Implementation Order
1. Create Entra users and groups.
2. Configure Intune enrollment.
3. Prepare WIN11-01.
4. Entra join / enroll the endpoint.
5. Create a Windows configuration profile.
6. Create a compliance policy.
7. Deploy an application.
8. Configure Defender Antivirus.
9. Configure Windows Firewall.
10. Configure BitLocker.
11. Configure MFA.
12. Configure Conditional Access.
13. Test compliance and policy behavior.
14. Perform troubleshooting scenarios.
15. Record incidents and resolutions.

## Security Notes
- Use a dedicated test account for Conditional Access testing.
- Keep an emergency/break-glass administrative account excluded from test policies where appropriate.
- Never publish real passwords, tokens, recovery codes, or tenant secrets in GitHub.
- Blur personal email addresses and tenant identifiers in screenshots.

## Suggested Resume Entry
**Azure Endpoint Management & Zero-Trust IT Operations Lab**
- Implemented Microsoft Intune-based Windows endpoint management with Entra ID identity, device enrollment, configuration and compliance policies, application deployment, Defender, Firewall, BitLocker, MFA, and Conditional Access.
- Troubleshot device compliance, policy synchronization, application deployment, and Conditional Access sign-in issues and documented incident resolutions.

## Skills Demonstrated
Microsoft Azure, Microsoft Entra ID, Microsoft Intune, Windows 11, Endpoint Management, Device Compliance, Configuration Profiles, Application Deployment, Microsoft Defender, Windows Firewall, BitLocker, MFA, Conditional Access, Zero Trust, RBAC, PowerShell, IT Troubleshooting.
