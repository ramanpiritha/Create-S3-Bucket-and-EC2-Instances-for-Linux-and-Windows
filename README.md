 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
 # Date: 20-11-24
 # Name: Piritharaman R
 # Reg no: 212223230148
 ## AIM
     To Create S3 bucket and EC2 Instances for Linux and Windows.
 ## PROBLEM STATEMENT
   This experiment aims to demonstrate the creation of an Amazon S3 bucket for storage purposes and the setup of EC2 instances for both Linux and Windows operating systems using AWS. Amazon S3 (Simple Storage Service) provides secure and scalable object storage, while EC2 (Elastic Compute Cloud) allows users to deploy virtual servers for computation and application hosting. 
## ALGORITHM
Steps 1:Login to AWS Management Console: Open the AWS Management Console. Navigate to the S3 service for bucket creation and EC2 for instance setup.
Steps 2:Create an S3 Bucket: Go to the S3 service. Click on Create bucket. Provide a unique Bucket Name and select the Region. Configure additional settings as per requirements and click Create bucket.
Steps 3:Launch EC2 Instance (Linux): Go to the EC2 service. Click on Launch Instance. Choose an Instance Type (e.g., t2.micro). Configure instance settings, key pair, and security groups, then Launch the instance.
Steps 4:Launch EC2 Instance (Windows): Repeat the EC2 launch steps but select a Windows Server AMI. Complete instance configuration and Launch.
Steps 5:Connect to Instances
## COMMANDS
```
S3 Bucket Creation
1.AWS CLI Command:
aws s3 mb s3:// --region
2.EC2 Instance (Linux) Commands:
Launch Linux EC2 instance and set up SSH access.
3.EC2 Instance (Windows) Commands:
Launch Windows EC2 instance and connect using RDP.
```
## OUTPUT
S3 Bucket:
![Screenshot (63)](https://github.com/user-attachments/assets/3a25b170-77e3-44a4-99a8-68b33ff26f2c)
LINUX Instance:
![image](https://github.com/user-attachments/assets/15a57d57-8b47-4d63-b715-bfdc0f016472)
WINDOWS Instance:
![WhatsApp Image 2024-11-20 at 6 57 23 PM](https://github.com/user-attachments/assets/f5abab04-7479-4395-80f1-712384c6861e)

## RESULT
S3 bucket and launch EC2 instances for Linux and Windows is successfully completed.

  


