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
| William Johnson | Managing Director | Management |
| Mary Kila | Office Administrator | Administration |
| Peter Aisi | Sales Officer | Sales |
| Daniel Kora | Driver | Operations |
| Samuel Puka | Vehicle Detailer | Operations |

## User Accounts
| Display Name | UserName |
|----------|-----------------------------|
| William Johnson | william@willztransport.com |
| Mary Kila | mary@willztransport.com |
| Peter Aisi | peter@willztransport.com
| Daniel Kora | daniel@willztransport.com |
| Samuel Puka | samuel@willztransport.com |

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

