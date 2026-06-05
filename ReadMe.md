# Lab 1 - Introduction to AWS Identity and Access Management (IAM)
# NAME : SANJAY A
## REGISTER NO: 212224040288
# Title
Introduction to AWS Identity and Access Management (IAM)

## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.

## Prerequisites
Basic understanding of cloud computing concepts
AWS Academy Lab access
Web browser with internet connectivity
## Tools Used
AWS Management Console
AWS Identity and Access Management (IAM)
Amazon EC2
Amazon S3
## Tasks Performed
# Task 1: Explore IAM Users and Groups
Reviewed pre-created IAM users: user-1, user-2, user-3
Explored IAM groups: EC2-Admin, EC2-Support, S3-Support
Inspected managed and inline policies attached to groups
Screenshot:
<img width="1350" height="592" alt="image" src="https://github.com/user-attachments/assets/8e4b9827-0d3f-4d44-bc36-76b5e8c9f0b9" />

# Task 2: Add Users to Groups
Added user-1 to the S3-Support group
Added user-2 to the EC2-Support group
Added user-3 to the EC2-Admin group
Screenshot:
<img width="1338" height="596" alt="image" src="https://github.com/user-attachments/assets/3e239772-dee6-4dc9-81ad-05dd2422501e" />
<img width="1336" height="592" alt="image" src="https://github.com/user-attachments/assets/4b499203-b52a-4326-9938-bb516d85ffbb" />
<img width="1334" height="596" alt="image" src="https://github.com/user-attachments/assets/e4b7d6ca-d8d1-4420-a412-a51b3847cb34" />


# Task 3: Test IAM User Permissions
Logged in using IAM sign-in URL
Verified S3 access for user-1
Verified EC2 read-only access for user-2
Verified EC2 administrative access for user-3
Screenshot:
<img width="1344" height="590" alt="image" src="https://github.com/user-attachments/assets/2bf05c33-902a-4df7-afe8-0669ab614ef1" />
<img width="1341" height="599" alt="image" src="https://github.com/user-attachments/assets/80f75c88-1bc1-4d7a-991b-e699dd7263ba" />

# Workflow
Accessed IAM console and reviewed users and groups.
Inspected policy permissions attached to groups.
Assigned users to groups based on their roles.
Logged in as each IAM user using the sign-in URL.
Validated permissions by accessing AWS services.
# Learning Outcomes
Understood the role of IAM in AWS security.
Learned how IAM users, groups, and policies interact.
Gained practical experience implementing role-based access control.
Verified permission enforcement through real-time service testing.
# Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.
