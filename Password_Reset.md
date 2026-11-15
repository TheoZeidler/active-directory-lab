# Scenario 1: Resetting a User's Password in Active Directory

## Overview

**Scenario:** A domain user has forgotten their password and is unable to log in to their workstation.

**Objective:** Use Active Directory Users and Computers (ADUC) to reset the user's password and restore access to their device.

Tools Used:

Windows Server 2025

Active Directory Domain Services (AD DS)

Active Directory Users and Computers (ADUC)

Windows client workstation

**Step 1**: Identify the Problem

The user is unable to access their workstation because they have forgotten their domain password.



The user attempts to log in but cannot authenticate with their existing credentials.


<img width="1512" height="982" alt="Screenshot 2026-11-04 at 8 45 24 PM" src="https://github.com/user-attachments/assets/757e8538-42d3-49af-a4b8-74dd569f267f" />


**Step 2:** Locate the User in Active Directory

Open Active Directory Users and Computers on the domain controller.

Navigate to the appropriate organizational unit (OU).

Locate the account belonging to the user.

<img width="1512" height="982" alt="Screenshot 2026-11-04 at 8 49 16 PM" src="https://github.com/user-attachments/assets/3a847b9a-d1c0-4bc3-ab80-f5c56d03fdca" />


**Step 3:** Reset the User's Password

Right-click the user's account.

Select Reset Password.

Enter a temporary password that meets the domain's password policy.

Select User must change password at next logon.

Confirm the password reset.

<img width="446" height="198" alt="Screenshot 2026-11-04 at 8 49 39 PM" src="https://github.com/user-attachments/assets/7fe503ce-d510-4bf4-b066-e56e24a9f3e9" />


**Step 4:** Verify the Password Reset

After resetting the password, the user can attempt to log in using their username and temporary password.


The user is prompted to create a new password upon their next login.


<img width="1512" height="982" alt="Screenshot 2026-11-04 at 8 51 51 PM" src="https://github.com/user-attachments/assets/842f29c4-9e6d-4a7e-bfd6-07992d77cb1a" />


**Step 5:** Confirm Successful Login

The user successfully authenticates with their new password and regains access to their workstation.

<img width="1512" height="982" alt="Screenshot 2026-11-04 at 8 52 37 PM" src="https://github.com/user-attachments/assets/08d70c08-e29d-49d5-8329-d2ef9a404f1f" />

##Outcome

<ins>Successfully resolved the user's login issue.</ins>

This exercise demonstrates the ability to:

Locate and manage domain user accounts.

Reset passwords using Active Directory Users and Computers.

Configure the requirement for users to change their temporary password at next logon.

Troubleshoot and resolve basic domain authentication issues.

Verify that a password reset successfully restores user access.
