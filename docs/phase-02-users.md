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

**Note:** This project is using the lab tenant without a custom domain, thus the usernames look like example@DSTechServices2026.onmicrosoft.com. These represent users who would use @willztransport.com in a production environment.

## Task 1 - Navigate to Microsoft 365 Admin Center
Go to:
Microsoft 365 Admin Center > Users > Active Users > Add a user

## Task 2 - Create User: Chase Patrol
Fill in:

| Field | Value |
|----------|-----------------------------|
| First Name | Chase |
| Last Name | Patrol |
| Display Name | Chase Patrol |
| Username | chase@DSTechServices2026.onmicrosoft.com *(Lab)* |
| Job Title | Director |
| Department | Management |
| Location | Lae |
| Country | Papua New Guinea |

Enable:
- [x] Create password automatically
- [x] Require password change on first sign-in

## Screenshot
Screenshot showing user 'Chase Patrol'.
File Path: screenshots/phase-02/CreateChase.png

## Task 3 - Repeat for Repeat for Remaining Users.

Create:
- Liberty Patrol
- Skye Patrol
- Zuma Patrol
- Rubble Patrol
- Liberty Patrol

## Task 4 - Verify Active Users

After creating all users:

Navigate to:
Users > Active Users
Verify all five users appear.

Take a screenshot:
File Path: screenshots/phase-02/ActiveUsers.png

## Task 5 - Configure User Details

Open each user and complete additional profile information where appropriate.
- Job Title
- Department
- Location

## Task 6 - Password Policy

Ensure each account:
- Uses a strong temporary password
- Is required to change the password at first sign-in

