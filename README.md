# Ex:4 Deployment and configuration of a Private Cloud in AWS
# Name:Sharon Harshini L M
# Reg No:212223040193

## Aim:
To set up of a Private Cloud in AWS.

## Setting up of a private cloud in AWS:
Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC), involves creating a logically isolated virtual network that you can use to launch AWS resources. This provides you with full control over your virtual networking environment, including resource placement, connectivity, and security. Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console. Next, add resources to it such as Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS) instances. Finally, define how your VPCs communicate with each other across accounts, Availability Zones, or AWS Regions.

## Procedure:

### Plan Your VPC:
● Determine your needs:

### Define your use case, including application requirements, security needs, and compliance standards.

● Plan IP address ranges:

### Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.

● Select Availability Zones:

### Decide which Availability Zones (AZs) you'll use for your resources, considering redundancy and performance.

● Plan internet connectivity:

### Determine if you need public internet access and how to configure it.

● Define security:

### Plan your security groups, network ACLs, and access controls to ensure a secure environment.

### Create Your VPC:
• Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.

• Choose "Create VPC": Initiate the VPC creation process.

• Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and other necessary settings.

• Create subnets: Define subnets within your VPC to isolate different parts of your network.

• Create route tables: Specify how traffic is routed within and outside the VPC.

• Create security groups: Define access control rules for your resources.

### Deploying Resources:
• Launch EC2 instances: Create and launch virtual machines within your VPC.

• Set up RDS instances: Deploy databases for your applications.

• Configure networking: Connect your resources to the appropriate subnets, security groups, and route tables.

• Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

### Managing and Monitoring:

• Use AWS CloudWatch: Monitor your VPC and resources for performance and health.

• Configure logging and auditing: Track access and activity within your VPC for security and compliance.

• Implement security best practices: Regularly review and update your security configuration.

• Scale and adjust as needed: Adjust your VPC infrastructure to meet changing demands.

## Output:

### Snapshot 1: Create VPC image
<img width="1220" height="707" alt="image" src="https://github.com/user-attachments/assets/d6a1a491-9d0d-4570-a326-b53aa9e56542" />

### Snapshot 2: Configuring Subnets
<img width="1203" height="559" alt="image" src="https://github.com/user-attachments/assets/47a8366a-e322-49ba-97ab-13fb9a65fb01" />

### Snapshot 3: Configure Subnets
<img width="1209" height="682" alt="image" src="https://github.com/user-attachments/assets/e0caf9c7-fd40-4f53-b6d0-9049f610414e" />

### Snapshot 4: Setting Internet gateway
<img width="1214" height="590" alt="image" src="https://github.com/user-attachments/assets/473b7418-9700-4bb1-a128-6e6b329cda33" />

### Snapshot 5: Creating Internet gateway
<img width="1210" height="713" alt="image" src="https://github.com/user-attachments/assets/2a5472ae-4d7d-4cbb-a22e-8e5a3e7ee923" />

### Snapshot 6: Setting Internet gateway
<img width="1211" height="582" alt="image" src="https://github.com/user-attachments/assets/94bb2878-bf6f-491d-baad-bd43c424330a" />

### Snapshot 7: Creating route table
<img width="1209" height="621" alt="image" src="https://github.com/user-attachments/assets/b266888a-a506-4bb4-87ef-689a3237c8fc" />

### Snapshot 8: Configuring route table
<img width="1214" height="736" alt="image" src="https://github.com/user-attachments/assets/454c9f05-7667-4bf3-80bd-87e694fe4b3c" />

### Snapshot 9: Editing routes
<img width="1216" height="578" alt="image" src="https://github.com/user-attachments/assets/986daab9-7801-4fff-8697-a92f5d7b34e9" />

### Snapshot 10: Creating route table
<img width="1211" height="571" alt="image" src="https://github.com/user-attachments/assets/2dc3435e-8c6a-4755-bde7-6077f3bf63d4" />

## Result:
Thus, a private cloud on AWS involves using VPCs has been created for a dedicated, isolated network where we can manage our resources and control access according to our requirements.
