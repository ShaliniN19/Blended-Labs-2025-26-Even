# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
  <img width="1358" height="552" alt="image" src="https://github.com/user-attachments/assets/1638671f-393c-426d-b9a4-1fd6e1bbbc4f" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1334" height="563" alt="image" src="https://github.com/user-attachments/assets/ef7a28ea-5c55-4717-af80-9762561fce3a" />
<img width="1317" height="556" alt="image" src="https://github.com/user-attachments/assets/b7d8133b-76df-4b62-8442-318fa3e3d9ae" />
<img width="1333" height="563" alt="image" src="https://github.com/user-attachments/assets/55b52534-08da-4a27-8d0a-3a2e8262ee18" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
  <img width="1363" height="555" alt="image" src="https://github.com/user-attachments/assets/781232c5-7552-4b3b-8bcb-e2daad7041ad" />

<img width="1336" height="564" alt="image" src="https://github.com/user-attachments/assets/cd362461-44a3-4ed6-bf0f-3ceb3a2d93be" />


## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Shalini.N and (Reg No):212224040305
**Course:** Introduction to Cloud Computing  

