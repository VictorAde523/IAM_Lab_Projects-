# IAM_Lab_Projects-
# Okta Fundamentals – Hands-On Practice & Notes

This repository contains hands-on labs, notes, and practice configurations based on the **"Okta Fundamentals with Okta Identity Engine"** Udemy course by Bryan Ferragamo.

## Course Overview

The course covers the core concepts and practical configurations involved in Okta Identity and Access Management (IAM), including:

- Okta Developer Console setup
- Identity types (users, groups, admins)
- Authentication policies
- Single Sign-On (SSO)
- Multi-Factor Authentication (MFA)
- Application integrations
- Lifecycle management
- Okta Workflows (intro level)

---

## Tools & Technologies

- **Okta Developer Account** (https://developer.okta.com)
- Okta Identity Engine
- Sample web app (for testing SSO & MFA flows)
- GitHub (for documentation)
- Optional: Postman (API testing)

---

## Hands-On Labs & Practice

### 1. Okta Developer Account Setup
- Created developer tenant at `dev-[subdomain].okta.com`
- Explored Admin Console: Dashboard, Directory, Security, Applications

### 2. User & Group Management
- Created test users manually and via CSV import
- Created custom groups (e.g., Engineering, HR)
- Assigned users to groups for role-based access control

### 3. App Integration & SSO
- Integrated sample app using OIDC
- Set up login redirect URI, client ID/secret
- Tested SSO login flows
- Configured app assignment for groups

### 4. Multi-Factor Authentication (MFA)
- Enabled MFA policies for specific groups
- Configured Okta Verify & SMS as authenticators
- Tested step-up authentication

### 5. Sign-On & Access Policies
- Created custom sign-on policies (e.g., geo-based, IP restrictions)
- Configured session timeouts
- Assigned different policies to apps

### 6. Lifecycle Management
- Created automation rules for user provisioning and deprovisioning
- Tested account suspension based on status changes
- Set up password policies

### 7. Intro to Okta Workflows
- Reviewed flow builder UI
- Sample: auto-assign user to group after app assignment

---

## Screenshots

[UC-27a59908-1dbc-4b9f-ba48-18386100c047.pdf](https://github.com/user-attachments/files/19686942/UC-27a59908-1dbc-4b9f-ba48-18386100c047.pdf)
![Screenshot 2025-04-10 102431](https://github.com/user-attachments/assets/611c8d30-f5f6-4c2b-8fa9-789c1f2e6eef)
![Screenshot 2025-04-10 102636](https://github.com/user-attachments/assets/5801a8f8-a707-46a6-a702-d76eb580630a)
![Screenshot 2025-04-10 102729](https://github.com/user-attachments/assets/16931f21-1f45-4065-ac59-fa4b674e1a2e)
![Screenshot 2025-04-10 102226](https://github.com/user-attachments/assets/54a95cc7-c6e1-4939-a0fc-2b10c2e750ab)
![Screenshot 2025-04-10 102242](https://github.com/user-attachments/assets/e47e5db0-60ac-46e8-baf3-b3d2afb4c60d)
![Screenshot 2025-04-10 102323](https://github.com/user-attachments/assets/15aa8228-ab1a-46d9-ba34-ac7138a5b81d)
![Screenshot 2025-04-10 102355](https://github.com/user-attachments/assets/716f3832-fd26-44db-9926-a2b24fa8e4f8)
![Screenshot 2025-04-10 102417](https://github.com/user-attachments/assets/8b9073ab-a137-4c58-9057-478d8d680b86)


---

## What I Learned

- Practical IAM configuration using Okta
- Core differences between Identity Providers (IdPs) and Service Providers (SPs)
- Real-world implementation of SSO and MFA
- How policy-based access management works
- Integrating Auth0 and OIDC + Postman

---

## Next Steps

- Complete Okta Certified Professional exam
- Complete AWS CLoud Practitioner exam
- Practice more on integrating with third-party apps
- Learn about Okta API & automation using Workflows or Terraform

---

## Author
Victor Adekola 

