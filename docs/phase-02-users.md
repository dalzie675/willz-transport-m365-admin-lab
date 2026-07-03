## Phase 2 - User Provisioning

## Objective

Create Microsoft 365 user accounts for all employees of **WILLZ Transport Ltd**, assign usernames, configure user properties, and prepare the accounts for licensing and collaboration.

## Business Scenario
**WILLZ Transport Ltd** has five employees. They require Microsoft 365 accounts to access:
- Outlook
- Microsoft Teams
- SharePoint
- OneDrive
- Microsoft Office applications (depending on license)

## Deliverables:
At the end of this phase:
- [x] Five users created
- [x] User information completed
- [x] Temporary passwords generated
- [x] Users required to change password at first sign-in
- [x] Departments configured
- [x] Job titles configured
- [x] Office location configured

## Employees
| Name | Position | Department |
|----------|-----------------------------|-----------------| 
| Chase Patrol | Director | Management |
| Skye Patrol | Managing Director | Management |
| Zuma Patrol | Sales Officer | Sales |
| Rubble Patrol | Driver | Asministration |
| Liberty Patrol | Vehicle Detailer | Administration |

## User Accounts
| Display Name | UserName |
|----------|-----------------------------|
| Chase Patrol | chase@DSTechServices2026.onmicrosoft.com |
| Skye Patrol | skye@DSTechServices2026.onmicrosoft.com |
| Zuma Patrol | zuma@DSTechServices2026.onmicrosoft.com |
| Rubble Patrol | rubble@DSTechServices2026.onmicrosoft.com |
| Liberty Patrol | liberty@DSTechServices2026.onmicrosoft.com |

**Note:** This project is using the lab tenant without a custom domain, thus the usernames look like example@DSTechServices2026.onmicrosoft.com. These represent users who would use @willztransport.com in a production encironment.

## Task 1 - Create the Microsoft 365 Tenant
## Goal
Provision a new Microsoft 365 tenant

Example:
Company Name: WILLZ Transport Ltd
Tenant Name: willztransport
Initial Domain: willztransport.onmicrosoft.com

## Project Note:
This deployement was completed in a Microsoft 365 lab tenant named **DSTechServices2026.onmicrosoft.com**. In a production environment, the tenant would use the customer's verified custom domain **willztransport.com** for all user accounts and email addresses.

## Screenshot
Screenshot showing Microsoft 365 Admin Center, Tenant Name, Tenant Domain
File Path: screenshots/phase-01/TenantCreated.png

## Task 2 - Configure Company Profile
Navigate to:
  Settings > Org settings > Organization Profile > Organization Information

## Organization Profile

| Setting | Value |
|----------|-----------------------------|
| Company Name | WILLZ Transport Ltd |
| Address | P.O. Box 123, Lae, 411, Morobe Province, Papua New Guinea |
| Phone | +675 7123 4567 |
| Technical Contact | IT Administrator |
| Email | admin@willztransport.com |
| Preferred Language | English |
| Time Zone | (UTC+10:00) Port Moresby |

## Screenshot
Screenshot showing Organization Profile settings.
File Path: screenshots/phase-01/ConfigureCompanyProfile.png

