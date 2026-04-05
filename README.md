# Enterprise IAM Lab for Google Workspace
Simulated IAM environment for workforce identity management This lab demonstrates key identity and access management (IAM) concepts using Google Workspace, including user lifecycle management, role-based access control, MFA, and secure SaaS provisioning.


# Users & Groups
Created user accounts representing typical departments:

| User                     | Role     | Department         |
| -------------------------| -------- | ------------------ |
| [jane@undefinedthegod.com] | HR Admin | HR |
| [evan@undefinedthegod.com] | IT Admin | IT |
| [john@undefinedthegod.com] | Employee | General Staff |
| [nick@undefinedthegod.com] | Employee | General Staff |

![Alt Text](/screenshots/users.png)
![Alt Text](/screenshots/groups.png)

# Access Controls & Policies
Implemented enterprise-level access management:

* MFA Enforcement:
Required for all users  

* Role-Based Access Control (RBAC):
Users assigned to groups with predefined permissions  

* Organizational Units (OUs):
Segmented departments to apply specific policies

![Alt Text](/screenshots/mfa.png)
Enforcing all users to use MFA and avoiding text or phone call methods for added security
![Alt Text](/screenshots/groupaccess.png)
Using these access settings to practice Separation of duties
![Alt Text](/screenshots/organizationalunits.png)
Segmented departments using OUs 
![Alt Text](/screenshots/passwordpolicy.png)
Thankfully, Google by default uses a strong password policy 

# User Lifecycle Management
Simulated provisioning and deprovisioning workflows:

Provisioning: New user added → assigned to groups → granted access to apps  

Deprovisioning: User removed → access revoked automatically
![Alt Text](/screenshots/provisioning.png) 
![Alt Text](/screenshots/deprovisioning.png)

# App Integrations
* Integrated Google Workspace apps (Gmail, Drive, Calendar) into group-based permissions  

* Configured access policies aligned with department roles
![Alt Text](/screenshots/app1.png) 
![Alt Text](/screenshots/app2.png)

# Documentation & Learnings
* Documented IAM workflows for onboarding/offboarding
* Applied least privilege principle to all users
* Simulated enterprise-grade SaaS security controls
* Gained hands-on experience with identity lifecycle, MFA, and RBAC
