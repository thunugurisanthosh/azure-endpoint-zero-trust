# Architecture

## Logical Flow

User
→ Microsoft Entra ID
→ Authentication / MFA
→ Conditional Access
→ Intune device compliance
→ Windows endpoint
→ Security controls

## Components

### Microsoft Entra ID
- Test users
- Security groups
- Role-based access
- Authentication

### Microsoft Intune
- Windows enrollment
- Configuration profiles
- Compliance policies
- Application deployment
- Endpoint security

### Windows Endpoint
- WIN11-01
- Windows 11
- Company Portal
- Defender
- Firewall
- BitLocker

### Conditional Access
- Require MFA
- Require compliant device
- Test blocked/non-compliant access
