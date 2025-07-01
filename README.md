# AWS Identity and Access Management Mini Project

## Project Overview
This 2-hour mini-project explores AWS IAM for GatoGrowFast.com, creating users (Eric, Jack, Ade), groups, and policies to secure EC2 and S3 resources, executed on Ubuntu (WSL) with VS Code via Ubuntu.

## Setup
- Initiated on Jul 01, 2025, 12:03 PM WAT.
- Used Ubuntu terminal (WSL) with VS Code, documenting in ~/Documents/Workspace/AWS_IAM_Mini_Project.

## Project Execution

### 1. Log In and Navigate to IAM Dashboard
- Logged into AWS Management Console and accessed IAM dashboard.

### 2. Part 1 - Create Policy and User for Eric
- **EC2 Policy**: Created “GatoEC2Policy” for full EC2 access.
- **User Eric**: Created with console access, attached “GatoEC2Policy,” and saved credentials.

### 3. Part 2 - Create Group and Users for Jack and Ade
- **Development-Team Group**: Created group without initial policy.
- **User Jack**: Created, added to “development-team.”
- **User Ade**: Created, added to “development-team.”
- **EC2 and S3 Policy**: Created “GatoDevPolicy” for full EC2 and S3 access.
- **Attach Policy**: Attached “GatoDevPolicy” to “development-team.”

### 4. Test and Validate Access
- **Eric’s Access**: Logged in, confirmed EC2 access, no S3 access.
- **Jack’s and Ade’s Access**: Logged in, confirmed EC2 and S3 access, no other services.

### Project Reflection
- **Understanding IAM**: IAM acts as a gatekeeper, controlling access to AWS resources to maintain security and order.
- **Security Importance**: Ensures protection of sensitive data, compliance, and prevents unauthorized access for GatoGrowFast.com.
- **Policy Creation**: Learned to create policies (e.g., “GatoEC2Policy”) by selecting services, actions, and resources, attaching to users/groups.
- **Practical Application**: Set up users, groups, and policies, enhancing real-world IAM skills with least privilege enforcement.

## Tools Used
- **Ubuntu Terminal (WSL)**: For documentation.
- **VS Code**: For editing `README.md`.
- **Git Bash**: For version control (optional).
- **AWS Management Console**: For IAM management.

## Conclusion
This project successfully implemented IAM for GatoGrowFast.com, securing resources with tailored policies and groups, aligning with best practices.