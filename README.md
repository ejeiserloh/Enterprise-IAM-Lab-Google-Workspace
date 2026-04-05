# Enterprise-IAM-Lab-Google-Workspace
Simulated IAM environment for workforce identity management This lab demonstrates key identity and access management (IAM) concepts using Google Workspace, including user lifecycle management, role-based access control, MFA, and secure SaaS provisioning.


# Users & Groups
Created user accounts representing typical departments:

| User                     | Role     | Department         |
| -------------------------| -------- | ------------------ |
| [hr@undefinedthegod.com] | HR Admin | HR |
| [it@undefinedthegod.com] | IT Admin | IT |
| [finance@undefinedthegod.com] | Employee | General Staff |
| [sales@undefinedthegod.com] | Employee | General Staff |

![Alt Text](/screenshots/users.png)
![Alt Text](/screenshots/groups.png)

# Access Controls & Policies

Implemented enterprise-level access management:

MFA Enforcement: 
Required for all users
Role-Based Access Control (RBAC): 
Users assigned to groups with predefined permissions
Organizational Units (OUs): 
Segmented departments to apply specific policies

![Alt Text](/screenshots/mfa.png)
Enforcing all users to use MFA and avoiding text or phone call methods for added security
![Alt Text](/screenshots/groupaccess.png)
Using these access settings to practice Separation of duties
![Alt Text](/screenshots/organizationalunits.png)
Segmented departments using OUs 
![Alt Text](/screenshots/passwordpolicy.png)
Thankfully Google by default uses a strong password policy 
