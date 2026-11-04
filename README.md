# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
# Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS

# Name:Sathya Priyan S
# Reg No:212225230255

# Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
# Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
# Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
# Step 3: Create Bucket
Click the Create bucket button.
# Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
# Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
# Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
# Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
# Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
# Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
# Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


# Snap Shots:
 

<img width="1898" height="862" alt="Screenshot 2026-11-02 151839" src="https://github.com/user-attachments/assets/7ff9e9ff-e5cf-47c6-9010-2f4a9e0e1163" />




<img width="1915" height="887" alt="Screenshot 2026-11-02 152018" src="https://github.com/user-attachments/assets/7f1421e8-14c3-46a3-a49f-a2180046cd2c" />


<img width="1917" height="905" alt="Screenshot 2026-11-02 152443" src="https://github.com/user-attachments/assets/fec55ad1-a076-48f2-8ec6-893500c469ab" />

<img width="1917" height="900" alt="Screenshot 2026-11-02 152913" src="https://github.com/user-attachments/assets/4c962155-6e3f-469e-a8cd-62c56ce6718f" />

<img width="1917" height="877" alt="Screenshot 2026-11-02 153337" src="https://github.com/user-attachments/assets/4e4b810e-69aa-41e0-b95b-733a6a796c4f" />


<img width="1917" height="888" alt="Screenshot 2026-11-02 153534" src="https://github.com/user-attachments/assets/ea5bbdca-e0b6-4f85-9105-7e58e1168cb6" />


<img width="1917" height="781" alt="Screenshot 2026-11-02 154014" src="https://github.com/user-attachments/assets/fc6afef4-e2a1-4722-a8df-c534b0f7ed2c" />


<img width="1917" height="962" alt="Screenshot 2026-11-02 154749" src="https://github.com/user-attachments/assets/7a123e87-4656-441f-aa41-9dc9daa82b23" />

<img width="1917" height="847" alt="Screenshot 2026-11-02 155834" src="https://github.com/user-attachments/assets/abb64f3a-5053-437d-b31d-4aa679c8c6f0" />

<img width="1917" height="841" alt="Screenshot 2026-11-02 160736" src="https://github.com/user-attachments/assets/cf045899-c255-4128-8881-cc1bc8e75157" />

<img width="1041" height="495" alt="image" src="https://github.com/user-attachments/assets/a044be7d-9570-4c2b-88bb-7f46ccf8d5f6" />



# Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
