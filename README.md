# AWS IAM User & Role Management

This project demonstrates AWS Identity and Access Management (IAM) concepts by creating users, groups, roles, and custom policies following cloud security best practices.

---

## Project Overview

This project covers:

- Creating IAM Users
- Creating IAM Groups
- Assigning Users to Groups
- Attaching AWS Managed Policies
- Creating Custom IAM Policies
- Creating IAM Roles
- Applying Least Privilege Principle

---

## AWS Services Used

- AWS IAM

---

## Project Architecture

```
AWS Account
│
├── IAM User
│      └── cloud-admin-user
│
├── IAM Group
│      └── CloudAdmins
│
├── Managed Policy
│      └── AdministratorAccess
│
├── Custom Policy
│      └── S3ReadOnlyCustom
│
└── IAM Role
       └── EC2-S3-ReadOnly-Role
```

---

## Screenshots

| Step | Screenshot |
|-------|------------|
| IAM Dashboard | screenshots/01-iam-dashboard.png |
| IAM User Created | screenshots/02-user-created.png |
| IAM Group Created | screenshots/03-group-created.png |
| User Added to Group | screenshots/04-user-added-group.png |
| Custom Policy | screenshots/05-custom-policy.png |
| IAM Role | screenshots/06-role-created.png |

---

## Security Best Practices

- Principle of Least Privilege
- IAM Groups for Permission Management
- Managed and Custom Policies
- IAM Roles instead of Long-Term Credentials
- Role-Based Access Control (RBAC)

---

## Learning Outcomes

After completing this project I gained hands-on experience with:

- IAM Users
- IAM Groups
- IAM Policies
- IAM Roles
- Access Management
- AWS Security Best Practices

---

## Author

**Tanweer Ahmed**

Portfolio:
https://tanweerahmed.in

LinkedIn:
https://linkedin.com/in/shaik-tanweer-ahmed

GitHub:
https://github.com/shaiktanweer5
