# Password Reset Troubleshooting

## Scenario

A user was unable to sign in to their Windows domain account and contacted the IT Help Desk requesting a password reset.

The incident was documented in ServiceNow and assigned to the Help Desk for troubleshooting.

## Environment

- Windows Server 2022
- Active Directory Domain Services (AD DS)
- Windows 11 Client VM
- ServiceNow

## Troubleshooting Process

1. Reviewed the user's ServiceNow incident.
2. Located the user's account in Active Directory Users and Computers.
3. Reset the user's password to a temporary password.
4. Selected **User must change password at next logon**.
5. Had the user sign in using the temporary password.
6. The user changed the temporary password to a new password.
7. Verified successful domain authentication after the password change.
8. Documented the completed troubleshooting steps in ServiceNow.
9. Resolved the incident after confirming account access was restored.

## Skills Demonstrated

- Active Directory user administration
- Password reset procedures
- User authentication troubleshooting
- Temporary password management
- Windows domain authentication
- ServiceNow incident management
- Ticket documentation
- User access verification

## Screenshots
### ServiceNow Password Reset Ticket
Received a ServiceNow incident from a user who couldn't sign in and requested a password reset.
<img width="886" height="549" alt="Abel-Ticket-Request" src="https://github.com/user-attachments/assets/2148ade6-d0dc-42cf-96c2-fc3075fd0d9e" />


### Password Reset in Active Directory
Reset the user's password in Active Directory and required the user to change the temporary password at the next logon.
<img width="956" height="599" alt="Abel&#39;s-Password-Reset" src="https://github.com/user-attachments/assets/3da8c717-3cfb-49be-ba35-f994a2bd6481" />


### Successful Sign-In Verification
Verified that the user successfully changed the temporary password and authenticated to the Windows domain. The whoami command confirmed the correct domain account was signed in
<img width="1024" height="768" alt="Abel&#39;s-Password-change" src="https://github.com/user-attachments/assets/63a952fc-3478-404a-8613-2c4ab328175d" />

<img width="988" height="309" alt="Abel-whoami" src="https://github.com/user-attachments/assets/f60c31e2-9cf5-40ee-b2e6-bdb6b48d0651" />

### ServiceNow Work Notes
Documented the troubleshooting and resolution steps in ServiceNow after verifying that account access was restored.
<img width="883" height="894" alt="Abel&#39;s-ticket-post" src="https://github.com/user-attachments/assets/88e229ef-c26e-488c-a26c-a5dfb7ee691b" />

### ServiceNow Ticket Resolved

Resolved the ServiceNow incident after completing the password reset and confirming successful user authentication.
<img width="1897" height="217" alt="Abel&#39;s-ticket-Resloved" src="https://github.com/user-attachments/assets/e6955f96-72ae-480d-8903-23bae51cbb6f" />


## Conclusion (Outcome)

The user's password was successfully reset in Active Directory. The user changed the temporary password, successfully authenticated to the Windows domain, and regained access to the account. The incident was documented and resolved in ServiceNow.
