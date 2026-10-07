# New Employee Onboarding and Access Provisioning

## Scenario
HR submitted a request to create a new user account for Olivia Carter, who was joining the Accounting department.
The goal of this project was to simulate a common onboarding workflow involving account creation, access assignment, first-login password configuration, authentication verification, and ticket documentation.

## Environment
- Windows Server 2022
- Active Directory Domain Services 
- Windows Client VM
- ServiceNow
- VMware
## Tasks Completed
1. Reviewed the onboarding request in ServiceNow.
2. Created a new Active Directory user account for Olivia Carter.
3. Placed the account in the appropriate Organizational Unit (OU).
4. Added the user to the Accounting security group.
5. Required the user to change the temporary password at first logon.
6. Signed in to the Windows client using the new domain account.
7. Verified successful domain authentication using the `whoami` command.
8. Documented the completed onboarding work in ServiceNow.
9. Resolved the onboarding incident after verifying account access.

## Skills Demonstrated
- Active Directory user provisioning
- User account administration
- Organizational Unit management
- Security group membership
- Access provisioning
- First-logon password configuration
- Windows domain authentication
- ServiceNow ticket documentation
- New employee onboarding

## Screenshots
### ServiceNow Onboarding Request

Received an onboarding request for a new Accounting employee requiring a domain account and department access.

<img width="888" height="576" alt="01-onboarding-request" src="https://github.com/user-attachments/assets/d0ce783a-356d-4813-b500-f1adf31dbb11" />

### Active Directory Account Creation

Created the new employee account in Active Directory and placed the account in the appropriate Organizational Unit.

<img width="969" height="589" alt="Olivia-AD" src="https://github.com/user-attachments/assets/766ce3af-0f16-491b-8884-2e3b67c895dc" />

### Accounting Group Membership

Assigned the employee to the Accounting security group to provide the appropriate department access.

<img width="945" height="638" alt="Olivia-memebership" src="https://github.com/user-attachments/assets/8e6d71e4-e73a-40ec-b8e0-a226efaeb481" />

### Successful Domain Sign-In

Verified that the new employee completed the required first-logon password change and successfully authenticated to the Windows domain.
The whoami command confirmed that the correct domain account was signed in.

<img width="1024" height="768" alt="User-changing-Password-first-time-sign in" src="https://github.com/user-attachments/assets/fcef4023-e32c-4065-b611-b3072a61ab91" />

<img width="1022" height="343" alt="User-Verify-carter" src="https://github.com/user-attachments/assets/4c4b87b7-73c1-46fc-b62e-1b43ec1e9e63" />

### ServiceNow Resolution

Documented the completed account setup, access assignment, and authentication verification in ServiceNow.

<img width="1905" height="888" alt="User-account-confirmation" src="https://github.com/user-attachments/assets/4afc7962-a2e1-4bcc-ab22-8ab4876af0a2" />

### ServiceNow Ticket Resolved

Resolved the onboarding incident after confirming the new employee account was provisioned and tested successfully.

<img width="1900" height="819" alt="Final-remarks" src="https://github.com/user-attachments/assets/ca0293b7-243d-4ea9-9470-4b79fbadae8a" />

<img width="1901" height="216" alt="Reslove-confirmation" src="https://github.com/user-attachments/assets/6de6cbab-53b6-45e6-9f5e-5f1a5f9b7ccd" />

## Outcome

The new employee account was successfully provisioned in Active Directory, assigned the appropriate Accounting access, and verified through a successful domain sign-in. The onboarding request was documented and resolved in ServiceNow.
