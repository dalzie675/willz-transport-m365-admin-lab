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
| Rubble Patrol | Driver | Administration |
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

- [x] Basics

| Field | Value |
|----------|-----------------------------|
| First Name | Chase |
| Last Name | Patrol |
| Display Name | Chase Patrol |
| Username | chase@DSTechServices2026.onmicrosoft.com *(Lab)* |
| Job Title | Director |
| Department | Management |
| Office | Lae |
| Country | Papua New Guinea |

Check:
- [x] Automatically create a password
- [x] Require this user to change their password when they first sign-in

## Assign product licenses
Check:
- [x] Assign user a product license
- [x] Microsoft Fabric (Free)
- [ ] Office 365 E5

Lab Note: Office 365 E5 unchecked as no license for this lab. However, in a production environment, this would be checked.

## Screenshot
1. Screenshot showing Assign License to user Chase
File Path: screenshots/phase-02/AssignLicenseChase.png

2. Screenshot showing user Chase Patrol
File Path: screenshots/phase-02/ChasePatrol.png

## Task 3 - Repeat for Remaining Users.

Create:

## - Skye Patrol

Fill in:

- [x] Basics

| Field | Value |
|----------|-----------------------------|
| First Name | Skye |
| Last Name | Patrol |
| Display Name | Skye Patrol |
| Username | skye@DSTechServices2026.onmicrosoft.com *(Lab)* |
| Job Title | Managing Director |
| Department | Management |
| Office | Lae |
| Country | Papua New Guinea |

Check:
- [x] Automatically create a password
- [x] Require this user to change their password when they first sign-in

## Assign product licenses
Check:
- [x] Assign user a product license
- [x] Microsoft Fabric (Free)
- [ ] Office 365 E5

Lab Note: Office 365 E5 unchecked as no license for this lab. However, in a production environment, this would be checked.

## Screenshot
1. Screenshot showing Assign License to user Skye
File Path: screenshots/phase-02/AssignLicenseSkye.png

2. Screenshot showing user Skye Patrol
File Path: screenshots/phase-02/SkyePatrol.png

## - Zuma Patrol

Fill in:

- [x] Basics

| Field | Value |
|----------|-----------------------------|
| First Name | Zuma |
| Last Name | Patrol |
| Display Name | Zuma Patrol |
| Username | zuma@DSTechServices2026.onmicrosoft.com *(Lab)* |
| Job Title | Sales Officer |
| Department | Sales |
| Office | Lae |
| Country | Papua New Guinea |

Check:
- [x] Automatically create a password
- [x] Require this user to change their password when they first sign-in

## Assign product licenses
Check:
- [x] Assign user a product license
- [x] Microsoft Fabric (Free)
- [ ] Office 365 E5

Lab Note: Office 365 E5 unchecked as no license for this lab. However, in a production environment, this would be checked.

## Screenshot
1. Screenshot showing Assign License to user Zuma
File Path: screenshots/phase-02/AssignLicenseZuma.png

2. Screenshot showing user Zuma Patrol
File Path: screenshots/phase-02/ZumaPatrol.png

## - Rubble Patrol

Fill in:

- [x] Basics

| Field | Value |
|----------|-----------------------------|
| First Name | Rubble |
| Last Name | Patrol |
| Display Name | Rubble Patrol |
| Username | rubble@DSTechServices2026.onmicrosoft.com *(Lab)* |
| Job Title | Driver |
| Department | Administration |
| Office | Lae |
| Country | Papua New Guinea |

Check:
- [x] Automatically create a password
- [x] Require this user to change their password when they first sign-in

## Assign product licenses
Check:
- [x] Assign user a product license
- [x] Microsoft Fabric (Free)
- [ ] Office 365 E5

Lab Note: Office 365 E5 unchecked as no license for this lab. However, in a production environment, this would be checked.

## Screenshot
1. Screenshot showing Assign License to user Rubble
File Path: screenshots/phase-02/AssignLicenseRubble.png

2. Screenshot showing user Rubble Patrol
File Path: screenshots/phase-02/RubblePatrol.png

## - Liberty Patrol

Fill in:

- [x] Basics

| Field | Value |
|----------|-----------------------------|
| First Name | Liberty |
| Last Name | Patrol |
| Display Name | Liberty Patrol |
| Username | liberty@DSTechServices2026.onmicrosoft.com *(Lab)* |
| Job Title | Vehicle Detailer |
| Department | Administration |
| Office | Lae |
| Country | Papua New Guinea |

Check:
- [x] Automatically create a password
- [x] Require this user to change their password when they first sign-in

## Assign product licenses
Check:
- [x] Assign user a product license
- [x] Microsoft Fabric (Free)
- [ ] Office 365 E5

Lab Note: Office 365 E5 unchecked as no license for this lab. However, in a production environment, this would be checked.

## Screenshot
1. Screenshot showing Assign License to user Liberty
File Path: screenshots/phase-02/AssignLicenseLiberty.png

2. Screenshot showing user Liberty Patrol
File Path: screenshots/phase-02/LibertyPatrol.png

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

## Key Takeaways:

- Automatically generated passwords are not stored (in plain-text for security reasons) and cannot be viewed after the initial creation screen.
- Passwords should be copied or printed during user creation, otherwise, reset password.

