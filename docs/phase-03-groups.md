## Phase 3 - Groups

## Objective

- Create security groups
- Create Microsoft 365 groups
- Assign users to the appropriate groups.

## 1. Security Groups
These groups are for **controlling access to resources.**

Create:

| Group | Type | Members |
|----------|-----------------------------|-----------------| 
| WT-Management-SG | Security | Director & Managing Director |
| WT-Sales-SG | Security | Sales Officer |
| WT-Administration-SG | Security | Driver & Vehicle Detailer |
| WT-All-Staff-SG | Security | All employees |

## 2. Microsoft 365 groups
These groups are designed for **collaboration.**

Create:

| Group | Purpose |
|----------|-----------------------------|
| WT-Management | Management collaboration |
| WT-Sales | Sales collaboration |
| WT-Administration | Administration collaboration |

## Step 1 - Open Microsoft Entra
Go to **Microsoft Entra admin center**: https://entra.microsoft.com/#home

Open: Entra ID > Groups > All groups

Select: **New group**

## Step 2 - Create the first security group
Set:

**Group Type:** Security

**Group Name:** WT-Management-SG

**Description:** Security group for WILLZ Transport management staff.

**Membership Type:** Assigned

**Owners:** No owners selected

Add users Director & Managing Director

**Member:** Chase Patrol; Skye Patrol > Select > **Create**

**!!Refresh!!**

## Screenshot
1. Screenshot showing Security Group for WILLZ Transport management staff.

   File Path: screenshots/phase-03/WTManagementSG.png

## Step 3 - Repeat for the other security groups.

Create:

**WT-Sales-SG** and add user Sales Officer

**WT-Administration-SG** and add users Driver & Vehicle Detailer

**WT-All-Staff-SG** and add all five users

## Screenshot
1. Screenshot showing Security Group for WILLZ Transport sales staff.

   File Path: screenshots/phase-03/WTSalesSG.png

2. Screenshot showing Security Group for WILLZ Transport administration staff.

   File Path: screenshots/phase-03/WTAdministrationSG.png

3. Screenshot showing Security Group for WILLZ Transport all staff.

   File Path: screenshots/phase-03/WTAllStaffSG.png

## Step 4 - Create a Microsoft 365 Group

Select **New group**

Set:

**Group Type:** Microsoft 365

**Group Name:** WT-Management

**Description:** Security group for WILLZ Transport management staff.

**Membership Type:** Assigned

**Owners:** No owners selected

Add users Director & Managing Director

**Member:** Chase Patrol; Skye Patrol > Select > **Create**

**!!Refresh!!**

## Repeat for the other groups

Create:

**WT-Sales** and add user Sales Officer

**WT-Administration-SG** and add users Driver & Vehicle Detailer

## Key Takeaways:

- Security groups are primarily useful for controlling access to resources.
- Microsoft 365 Groups are designed for **collaboration** and can provide resources such as a shared mailbox, calendar, SharePoint site, and integration with Teams.
- The **WT-** prefix makes groups easy to identify in a real tenant.


