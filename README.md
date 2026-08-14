# Loctech IT-Training-Enugu-AWS-PROJECT_MRS.ANGEL
FinalCapstoneProject
EC2 + RDS WEB APPLICATION PROJECT
AWS Services

-EC2 — hosts the web application
-RDS MySQL — hosts the database
-VPC — provides the network
-Security Groups — controls traffic
-IAM — manages permissions
-Cloud Watch — monitoring
-S3 — optional storage for images/files.

What YOU should build

A simple application such as:
-Student Registration System
-Students should be able to:
-Register a student
-View registered students
-Update student information
-Delete a student
-Store the information in RDS MySQL

 The workflow:
 
Phase 1 — AWS Networking
-Create VPC
-Create public subnet
-Create private subnet
-Configure route tables
-Configure Internet Gateway
Phase 2 — EC2
-Launch Ubuntu EC2
-Configure Security Group
-Connect using SSH
-Install Apache/Nginx
-Deploy the application
Phase 3 — RDS
-Create MySQL RDS
-Configure database
-Create database/user
-Configure RDS Security Group
Phase 4 — Application
-Connect EC2 application to RDS
-Create database tables
-Implement CRUD operations
-Test the application
Phase 5 — Security
-Restrict SSH access
-Don't expose MySQL port 3306 to the internet
-Allow RDS traffic only from the EC2 Security Group
-Use IAM appropriately
