 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
  ## AIM
       To Create S3 bucket and EC2 Instances for Linux and Windows.
## PROBLEM STATEMENT
    The goal of this experiment is to demonstrate the creation of an Amazon S3 bucket for storage purposes and the setup of EC2 instances for both Linux and Windows operating systems using AWS. Amazon S3 (Simple Storage Service) provides secure and scalable object storage, while EC2 (Elastic Compute Cloud) allows users to deploy virtual servers for computation and application hosting.

## ALGORITHM
Step 1
Login to AWS Management Console:
Open the AWS Management Console.
Navigate to the S3 service for bucket creation and EC2 for instance setup.

Step 2
Create an S3 Bucket:
Go to the S3 service.
Click on Create bucket.
Provide a unique Bucket Name and select the Region.
Configure additional settings as per requirements and click Create bucket.

Step 3
Launch EC2 Instance (Linux):
Go to the EC2 service.
Click Launch Instance.
Select an Amazon Machine Image (AMI), such as Amazon Linux 2.
Choose an Instance Type (e.g., t2.micro).
Configure instance settings, key pair, and security groups, then Launch the instance.

Step 4
Launch EC2 Instance (Windows):
Repeat the EC2 launch steps but select a Windows Server AMI.
Complete instance configuration and Launch.

Step 5
Connect to Instances:
Linux Instance: Use SSH to connect.
ssh -i "key_pair.pem" ec2-user@<linux_public_dns>

Commands

S3 Bucket Creation
1.AWS CLI Command:
aws s3 mb s3:// --region

EC2 Instance (Linux) Commands
Launch Linux EC2 instance and set up SSH access.

EC2 Instance (Windows) Commands
Launch Windows EC2 instance and connect using RDP.

### REG NUMBER:Arunkumar S A
### NAME:212223220009
 

## OUTPUT
S3 bucket
![image](https://github.com/user-attachments/assets/97945d8a-4e8d-4fc6-a76c-da19a9c87f1e)
linux instance
![image](https://github.com/user-attachments/assets/229df7fa-299c-4362-aeb1-d848d48a7e98)
windows instance
![image](https://github.com/user-attachments/assets/a3454e4d-b0bf-490f-a5e6-7aed0366a75b)




## RESULT
 
The experiment to create an S3 bucket and launch EC2 instances for Linux and Windows is successfully completed.
  


