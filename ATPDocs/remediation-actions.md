---
title: Remediation actions in Microsoft Defender for Identity
description: Learn how to respond to compromised users with remediation actions in Microsoft Defender for Identity
ms.date: 04/14/2022
ms.topic: conceptual
---

# Remediation actions in Microsoft Defender for Identity

Applies to:

- Microsoft Defender for Identity
- Microsoft 365 Defender

If you've created [Microsoft Defender for Identity action accounts](manage-action-accounts.md), you can quickly respond to compromised users by disabling their accounts or reset their password. After taking action on users, you can check on the activity details in the action center.

Those response actions on users are available directly from the user page, the user side panel, the advanced hunting page, or in the action center.

The following actions can be performed directly on the on-premises account:

- **Disable user**: This will temporarily prevent a user from logging in to the network. This can help prevent compromised users from moving laterally and attempting to exfiltrate data or further compromise the network.
- **Reset user password** – This will prompt the user to change their password on the next logon, ensuring that this account can't be used for further impersonation attempts

> [!NOTE]
> For users with the **Password never expires** flag turned on, the password reset will only take place once the flag is removed.

## Prerequisites

These actions require setting up a privileged gMSA account that Microsoft Defender for Identity uses to perform the actions. You can read about the requirements in [Microsoft Defender for Identity action accounts](manage-action-accounts.md).

## Permissions

Currently, this feature requires the account signed into Microsoft 365 Defender to possess the **Security Administrator** role.

## Related videos

[Remediation actions in Defender for Identity](https://www.microsoft.com/en-us/videoplayer/embed/RE4U7Pe)

## See also

[Microsoft Defender for Identity action accounts](manage-action-accounts.md)