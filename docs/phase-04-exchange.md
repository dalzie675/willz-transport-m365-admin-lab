## Phase 4 - Exchange Online

## Objective

To configure Exchange Online for WILLZ Transport to support:

- A general enquiries shared mailbox
- Distribution lists
- Email aliases
- Automatic replies
- Appropriate mailbox permissions
- Basic testing and documentation

Microsoft recommends shared mailboxes for addresses such as info@company.com when multiple people need to monitor and respond from the same address.

## 1. Create the shared mailbox

Go to Exchange Admin Center: https://admin.cloud.microsoft/exchange/homepage

Mailboxes > Add a shared mailbox
	Display Name: WILLZ Transport General Enquiries
	Email: info@DSTechServices2026.onmicrosoft.com
Create.

Note: An error occurred as this current subscription is not licensed for Exchange. Refer error message below:
“Error executing request. The following error occurred during validation in agent 'Substrate Only Agent': 'Organization "DSTechServices2026.onmicrosoft.com" is not licensed for Exchange email functionality. Cmdlet usage is restricted.”

However, in a production environment, a shared mailbox would have been created.

## Thus, Exchange Online - Not Implemented

## Exchange Online functionality is not available in the current Entra ID Free tenant. The Exchange Online configuration is therefore being documented as a planned phase requiring an appropriate Microsoft 365 subscription. 

