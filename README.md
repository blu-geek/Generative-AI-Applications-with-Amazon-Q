
# Building Generative AI Applications with Amazon Q and Enhancing Knowledge Bases with Amazon Q Business

As an AI/ML Engineer,you are tasked with enhancing the company’s knowledge management system using Amazon Q Business and Amazon Q Apps. We will create a scalable, intelligent knowledge repository 
integrated with Amazon S3, configure advanced retrieval models, and set up secure access controls. 

The second task is to deploy AI-driven applications to automate tasks and generate insights,improving internal efficiency and customer support.We will be developing an App that enables the
marketing department to generate business proposals.


# AMAZON Q 

<img width="791" alt="Screenshot 2025-01-10 at 17 34 07" src="https://github.com/user-attachments/assets/53265053-a7e8-4b3c-bf70-4244c7c5d62f" />


# Amazon Q Apps


<img width="664" alt="Screenshot 2025-01-10 at 17 37 35" src="https://github.com/user-attachments/assets/29b005c3-04f1-42c8-ba43-e5bb82113d69" />


# AMAZON Q BUSINESS

<img width="777" alt="Screenshot 2025-01-10 at 17 34 32" src="https://github.com/user-attachments/assets/45e6b228-6488-49d0-b6db-8402ad8289b4" />


# Activity Guide

1. Enable IAM Identity Center (AWS IAM Identity Center)
Set Up User Management:
Navigate to the AWS Management Console and enable IAM Identity Center.
Define user groups and assign permissions based on organizational requirements.
Configure Access Controls:
Implement least-privilege policies for secure access.
Map users to roles to streamline access across AWS services.

2. Create Users (AWS IAM)
Add Users:
Create individual user accounts in IAM Identity Center.
Specify email addresses and generate temporary passwords for new users.
Assign Roles and Permissions:
Attach roles to users for accessing specific AWS resources, such as S3 and Amazon Q Business.

3. Set Up an S3 Bucket (Amazon S3)
Create the Bucket:
Use the S3 Console to create a bucket with a unique name.
Configure the bucket for your data storage needs.
Set Permissions and Policies:
Enable bucket-level permissions to ensure secure access.
Apply encryption and logging policies for compliance and tracking.

4. Configure Amazon Q Business (Amazon Q Business)
Initial Setup:
Access Amazon Q Business via the AWS Management Console.
Follow the onboarding wizard to configure the workspace.
Integrate the S3 Bucket:
Link the S3 bucket to Amazon Q Business for data input/output.
Ensure the proper permissions are assigned to allow seamless integration.
Assign User Access:
Grant access to users through IAM Identity Center, allowing them to utilize Amazon Q Business tools.

5. Explore Amazon Q Apps (Amazon Q Business)
Set Up Amazon Q Apps:
Launch pre-built Q Apps or create custom ones for your business needs.
Use the apps for data visualization, insights, and operational management.
Automate Tasks:
Automate repetitive workflows using Amazon Q Apps features.
Generate insights from connected data sources like S3.

6. Clean Up Resources (Amazon S3, IAM, Amazon Q Business)
Delete the S3 Bucket:
Empty the bucket and delete it to avoid unnecessary charges.
Remove Users and Applications:
Revoke user permissions in IAM Identity Center.
Deactivate and remove Amazon Q Apps and configurations.

