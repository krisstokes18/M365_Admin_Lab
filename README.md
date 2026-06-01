# M365 Admin Lab — Microsoft 365 Administration

## Overview

Hands-on Microsoft 365 administration lab using a Business Standard tenant with Entra ID P1. Built the environment from scratch to simulate day-one IT admin work. Covers identity management, Exchange Online, Teams administration, Conditional Access policies, and Defender for Business threat protection.

## Environment

- **Platform:** Microsoft 365 Business Standard with Entra ID P1 Trial
- **Tools Used:** Microsoft 365 Admin Center, Microsoft Entra ID, Exchange Online Admin Center, Teams Admin Center, Microsoft Defender Portal

## What I Did

### User and Identity Management
- Provisioned 6 user accounts from scratch with job titles and departments
- Assigned licenses to all users
- Assigned Helpdesk Administrator role to IT staff following least-privilege principles
- Created two security groups for IT staff and new hire onboarding
- Configured self-service password reset scoped to IT help desk group
- Reviewed sign-in logs for monitoring and audit visibility

### Conditional Access — Zero Trust Security
- Created Require MFA for All Users policy targeting all cloud apps
- Created Block Legacy Authentication policy preventing insecure sign-ins
- Created Require Compliant Device policy scoped to IT help desk staff
- All policies deployed in Report-only mode simulating production rollout workflow

### Exchange Online
- Managed user mailboxes across the tenant
- Created IT Help Desk shared mailbox with delegate permissions for IT staff
- Created All IT Staff distribution list
- Configured mail flow rule adding external sender warning banners to all inbound external email

### Teams Administration
- Created private IT Help Desk team with members assigned
- Configured custom meeting policy with cloud recording and transcription enabled

### Microsoft Defender
- Reviewed anti-phishing policy configuration
- Reviewed Defender portal security dashboard
- Checked tenant Secure Score and recommended improvement actions

## Skills Demonstrated

- Microsoft 365 tenant administration and license management
- Entra ID user and group management
- Role-based access control and least-privilege access
- Self-service password reset configuration
- Exchange Online mailbox and mail flow management
- Conditional Access policy creation and Zero Trust implementation
- Microsoft Defender threat policy review
- Identity and access management workflows

## Screenshots

### License Overview
![License Overview](docs/m365_license_overview.png)

### Active Users
![Active Users](docs/m365_active_users.png)

### User Created
![User Created](docs/m365_user_created.png)

### Full User List
![Full User List](docs/m365_full_user_list.png)

### Role Assigned
![Role Assigned](docs/m365_role_assigned.png)

### Security Group
![Security Group](docs/m365_security_group.png)

### Entra ID Users
![Entra ID Users](docs/m365_entra_users.png)

### Sign-In Logs
![Sign-In Logs](docs/m365_signin_logs.png)

### SSPR Configuration
![SSPR Config](docs/m365_sspr_config.png)

### Conditional Access Policy
![Conditional Access](docs/m365_conditional_access.png)

### CA Policies List
![CA Policies](docs/m365_ca_policies_list.png)

### Exchange Mailboxes
![Exchange Mailboxes](docs/m365_exchange_mailboxes.png)

### Shared Mailbox
![Shared Mailbox](docs/m365_shared_mailbox.png)

### Distribution List
![Distribution List](docs/m365_distribution_list.png)

### Mail Flow Rule
![Mail Flow Rule](docs/m365_mailflow_rule.png)

### Teams Admin
![Teams Admin](docs/m365_teams_admin.png)

### Meeting Policy
![Meeting Policy](docs/m365_meeting_policy.png)

### Defender Anti-Phishing
![Defender Anti-Phishing](docs/m365_defender_antiphishing.png)

### Defender Overview
![Defender Overview](docs/m365_defender_overview.png)

### Secure Score
![Secure Score](docs/m365_secure_score.png)
