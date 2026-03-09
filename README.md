# Certified-Cloud-Practioner


<details> <summary><strong>▶ DAY-1 </strong></summary>

**AWS INTRO**
**WHAT IS SERVER COMPOSED OF ?**

- Compute: cpu + memory : ram
- Storage : data
- Database : store data in a structured way
- Network : routers, switch, DNS server

**IT TERMINOLOGY**

- Network: cables, routers & servers connected with each other.
- Routers: a networking device that forwards data packets between computer
networks. They know where to send your packets on the internet.
- Switch: Takes a packet and it to the correct server/client on your network.

**PROBLEMS WITH TRADITIONAL IT APPROACH**

- Pay for the rent for the data center.
- Pay for power supply, coding, maintenance.
- Adding & replacing hardware takes time.
- Scaling is limited.
- Hire 24/7 team to monitor the infrastructure.
- How to deal with disasters ? (earthquake, power, shutdown, fire…. )
- Can we externalize all this ?

**WHAT IS CLOUD COMPUTING**

- Cloud computing is the on-demand delivery of compute power, database,
storage, applications & other IT resources.
- Through a cloud services platform with pay-as-you-go pricing.
- You can provision exactly the right type and size of computing resources you
need.
- You can access as many resources as you need, almost instantly.
- Simple way to access servers, storage, databases and a set of application
services.
- Amazon web services owns & maintains the network-connected hardware
required for these application services, while you provision & use what you
need via a web application.

EX:
1. GMAIL:
- E-mail cloud services
- pay for only your email stored
2. DROPBOX:
- Cloud storage service
- Originally built on AWS
3. NETFLIX:
- Built on aws
- Video on demand

**THE DEPLOYMENT MODELS OF THE CLOUD**

**1. PRIVATE CLOUD**
- Cloud services used by a single organization, not exposed to the public.
- complete control
- Security for sensitive applications.
- Meet specific business needs.

**2.PUBLIC CLOUD**
- Cloud services owned & operated by a third-party cloud service provider
delivered over the internet.

**3.HYBRID CLOUD**
- Keep some servers on premises & extend some capabilities to the cloud.
- Control over sensitive assets in your private infrastructure.
- Flexibility and cost-effectiveness of the public cloud.

**THE FIVE CHARACTERISTICS OF CLOUD COMPUTING**

- On-demand self service: Users can provision & use them without human
interaction from the service providers.
- Broad network access: Resources available over the network & can be
accessed by diverse client platforms.
- Multi tenancy & resource pooling:
   1. Multiple customers can share the same infrastructure & applications with
security & privacy.
   2. Multiple customers are serviced from the same physical resources.
- Rapid elasticity & scalability:
   1. Automatically & quickly acquire & dispose resources when needed.
   2. quickly & easily scale base on demand
- Measured services: Usage is measured, users pay correctly for what they
have used.

**SIX ADVANTAGES OF CLOUD COMPUTING**

- Trade capital expense (CAPEX) for operational expense (OPEX).
   1. Pay on demand: don’t own hardware.
   2. Reduces total cost of ownership (TCO) & operational expense (OPEX).
- Benefit from massive economics of scale.
   1. Prices are reduced as aws is more efficient due to large scale.
- Stop guessing capacity:
   1. Scale based on actual measured usage.
- Increased speed & agility.
- Stop spending money running & maintaining data centres.
- Go global in minutes: leverages the aws global infrastructure.

**PROBLEMS SOLVED BY THE CLOUD**

- Flexibility: change resource types when needed.
- Cost-effectiveness: pay as you go, for what you use.
- Scalability: accommodate larger loads by making hardware stronger or adding
additional nodes.
- Elasticity: ability to scale out & scale-in when needed.
- High-availability & fault tolerance: build across data centres.
- Agility: rapidly develop, test & launch software applications.

**TYPES OF CLOUD COMPUTING**

**Infrastructure as a service(IAAS):**
1. Provide building blocks for cloud IT.
2. Provides networking, computers, data storage space.
3. Highest level of flexibility.
4. Easy parallel will traditional on-premises IT.
   
**Platform as a service(PAAS):**
1. Removes the need for your organisation to manage the underlying
infrastructure.
2. Focus on the deployment & management of your applications.
   
**Software as a service(SAAS):**
1. Completed product that is run & managed by the service provider.
2. Availability zones
3. Regions
4. Edge locations

**CLOUD**

- We can store not only in physical device, we can store in online also.
- Cloud introduction in 1976.
- They call this theorem as a terminology (.) on premises
   1. physical server
   2. virtual machine
   3. cloud
- Cloud service provider
- Cloud service customer
   - RIR ⇒ Remote server - Internet - Rent

**WHAT IS AWS**

- It is a platform that offers flexible, reliable, scalable, easy to use and cost
effective cloud computing solutions.
- AWS entered market in 2006 only in north Virginia for test case.
- After few entertainments AWS entered INDIA on June 2016 in Mumbai.
- Currently AWS offers 200+ services.
- AWS, azure - Microsoft, GCP - google cloud platform, Alibaba, Tencent, IBM,
Orcale etc.
- AWS was in top range because as cheaper than other providers.
- HOW ? Pay as you go method

**DISADVANTAGES OF PREMISES**

- High maintenance, man power, huge cost, investment, suppose business loss
means we can’t sell the server. AWS can easily return server.

**ADVANTAGES OF AWS**

- AWS itself under server maintenance
- Reduce upfront cost.
- Provides Scalability
- Global reach
- High availability and Security

**AWS GLOBAL INFRASTRUCTURE**
- AWS regions
- AWS availability zones
- AWS data centers
- AWS edge locations/points of presence
- https://infrastructure.aws/

**AWS REGIONS**
- AWS has regions all around the world.
- Names can be us-east-1, eu-west-3
- A region is a cluster of data centres.
- most AWS services are region-scoped

**HOW TO CHOOSE AWS REGIONS**
- Compliance with data governance & legal requirements: data never leaves a
region without your explicit permission.
- Proximity to customers: reduced latency
- Availability services within a region: new services & new features aren’t
available in every region.
- Pricing: pricing varies region to region and is transparent in the service pricing
page.

**AWS AVAILABILITY ZONES**
- Each region has many availability zones(usually 3, min is 3, max is 6).
- EX:
   1. ap-south east-2a
   2. ap-south east-2b
   3. ap-south east-2c
- Each availability zone (AZ) is one or more, discrete data canters with
redundant power, networking & connectivity.
- They are separate from each other, so that they are isolated from disasters.
- They are connected with high bandwidth ultra-low latency networking.

**AWS POINTS OF PRESENCE (EDGE LOCATIONS)**

- Amazon has 700+ points of presence in 90+ cities across 40+ countries.
- Content is delivered to user with low latency.
- https://aws.amazon.com/cloudfront/features/

**AWS ACCEPTABLE POLICY**

- https://aws.amazon.com/aup/
- No illegal, harmful or offensive use or content.
- No security violations
- No network abuse
- No E-mail or other message abuse.

</details>

*********************************************************************************************************************************************************************************


<details> <summary><strong>▶ DAY-2 </strong></summary>
   
**IAM - Identity and Access Management**
   
- IAM is a Global service
- In IAM, we are going to create users and assign them to
groups
- We already using IAM without knowing in the name of Root
account
- The Root Account we created shouldn’t be used or Shared
- Groups only contain Users
- A user can belong to multiple groups.

**IAM - Permissions**
- To work on our account, We need to give permissions
- Users or Groups can be assigned a JSON document called
Policies
- We are giving permissions to users to work on allowed
resources
- In AWS, We don’t allow everyone to do everything
- Whatever the policies defined in the Statement of JSON file
(Refer below JSON file), these policies define the permissions
of the users.
- In AWS, You apply a principle called “least Privilege
Principle” which means you don’t give more permissions
than the user needs

**Hands On**
- Go to AWS Management Console
- Search for service “IAM” in search bar
- Click on “Users” and create a user for yourself
- Create a group called “Admin” and add
“Administrator Access” and assign the user
- Log in with your IAM account by editing your
custom URL (On right side)

**IAM Policies**
- Policies can be defined in JSON file

**IAM Policy Structure**

Policy Structure consists of
- Version: Policy Language Version
- ID: An Identifier for the Policy (Optional)
- Statement: One (or) More Individual Statements
- Statement Consists of:
- Sid: Statement ID
- Effect: Whether the statement allows or
denies
- Principal: Which user/role/account can comes
under this policy
- Action: List of calls they can take
- Resource: List of Resources to which the
actions applied to
- Condition: Conditions for when this policy is
in effect (optional)

{
   "Version": "2023-09-21",
   "Id": "S3-Account-Permissions",
   "Statement": [
      {
         "Sid": "1",
         "Effect": "Allow",
         "Principal": {
            "AWS": ["arn:aws:iam::123456789012:root"]
         },
         "Action": [
         "s3:GetObject",
          "s3:PutObject"
           ],
            "Resource": ["arn:aws:s3:::mybucket/*"]
         }
      ]

}

**Hands On**

- Go to “Policies” in IAM Dashboard
- Check a JSON file of any policy
- Can create a policy if needed
  
**Security**
- After creating Groups & Users
- It’s time to protect the users and groups from being
compromised
We have 2 Defense Mechanisms:

**1. Password Policy**
- Use Stronger Passwords
- In AWS, We can setup a password policy with different
options
- Min. Password length
- Requires specific character types
- Allow all IAM users to change their own passwords
- Requires users to change their password after
sometime (Password Expiration)
- Passwords Re Use
  
**2. MFA - Multi Factor Authentication**
- In AWS, It is must & very recommended to use it
- Users have access to your account and can possibly
change Configurations (or) delete resources in your
AWS account
- Protect the users to avoid all these
- Use MFA = Password + Security Device you own
- If someone having password + MFA, even if their
password has been stolen, the account is not
compromised.

**MFA Device Options in AWS**
- Virtual MFA Device
- Google Authenticator (Phone
- Authy (Multi Device)
- U2F (Universal 2nd Factor) Security Key by Yubiko (3rd
party)
- Hard key Fob MFA Device by Gemalto (3rd Party)
- AWS GovCloud (US) - Surepass ID (3rd Party)
  
**Hands On**
- Go to Account Settings and explore Password Policy by
editing (Custom)
- Go to IAM Dashboard and enable MFA
- Choose Authenticator App
- Download Twilio Authy App in your phone
- Scan the QR code and add account
- Click on Assign MFA
- Try logout and Login

**Note: If you lose your device, your AWS account will be locked
permanently.**

**IAM Access Keys, CLI & SDK:**
**How can users access AWS?**
- To access AWS, We have 3 ways
- AWS Management Console (Protected by Password +
MFA)
- AWS CLI (Protected by Access Keys)
- AWS SDK (Software Development Kit) - To call API’s
from AWS
- Users can manage their own access keys
- Access keys are secret, just like a password, Don’t share
them

**What is AWS CLI?**
To access AWS services using commands in your command
line shell
- With CLI, we get direct access to public APIs of AWS Services
- You can develop scripts to manage your resources
- It is an alternative to AWS Management Console

**What is AWS SDK?**
- SDK stands for “Software Development Kit”
- It enables you to access and manage AWS services
programmatically
- Need to integrate within our application
- It supports JS, Py, PHP, .Net, Ruby, Java etc
- AWS CLI is built on AWS SDK for python
**Another Way is AWS CloudShell within AWS Console
—-- Hands On —--**

**IAM Roles for Services:**
- Some AWS services will need to perform actions on your
behalf
- Like users, Services also needs some kind of permissions
- To do that, We will assign permissions to AWS services with
IAM Roles
- They will not be used by people but services
- Common roles are
- EC2 Instance Roles
- Lambda Function Roles
- Roles for Cloud Formation
**—-- Hands On —--
IAM Security Tools:
IAM Credentials Report (Account Level)**
- A report that lists all your account’s users and the status of
their various credentials
**IAM Access Advisor (User Level)**
- Access Advisor shows the service permissions granted to a
user and when the services were last accused.
- Using this, We can revise our policies

**—-- Hands On —--**
**IAM Best Practices & Guidelines**
  
- Don’t use the root account except for AWS account setup
- One Physical user = One AWS User
- Assign users to groups and assign permissions to groups
- Create a strong password policy
- Use and enforce the use of MFA
- Create and use roles for giving permissions to AWS Services
- Use access keys for programmatic access (CLI/SDK)
- Audit permissions of your account using IAM Credentials

**Report & IAM Access Advisor**
- Never share IAM users & access keys

**Shared Responsibility Model for IAM**
**AWS**                                     
1. Infrastructure (Global, Network, Security)
2. Configuration & Vulnerability Analysis
3. Compliance Validation

**Customer**
1. Users, Groups, Roles, Policies Management & Monitoring
2. Enable MFA on all accounts
3. Use IAM tools to apply appropriate permissions
4. Analyse access patterns & Review permissions

**IAM - Summary:
- Users:** Mapped to a physical user, has a password for AWS
Console.
- **Groups:** Contains users only
- **Policies:** JSON document that outlines permissions for users (or)
groups
- **Roles:** for EC2 instances (or) AWS Services
- **Security:** MFA + Password Policy
- **AWS CLI:** Manage your AWS services using Command - Line
- **AWS SDK:** Manage your AWS services using a Programmatic
language
- **Access Keys:** Access AWS using CLI or SDK
- **Audit:** IAM Credential Report & IAM Access Advisor

</details>

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
<details> <summary><strong>▶ DAY-3 </strong></summary>


- **EC2 Basics**
- **What is Amazon EC2?**
- Ec2 is one of the most popular services in AWS/Cloud
- EC2 → Elastic Compute Cloud → Infrastructure as a Service
- What EC2 consists of
- Renting Virtual Machines (EC2) → Instances
- Storing Data on Virtual Drives (EBS)
- Distributing Load across machines (ELB)
- Scaling the services using an Auto-Scaling Group (ASG)
→ Knowing EC2 is Fundamental to understand how the cloud works

**EC2 Sizing & Configuration Options**
- Operating System (OS): Linux, Windows, & Mac OS
- How much Compute Power & Cores (CPU)
- How much Random-Access memory (RAM)
- How much Storage Space:
- Network Attached (EBS & EFS)
- Hardware (EC2 Instance Store)
- Network Card: Speed of the card, Public IP Address
- Firewall Rules: Security Group
- Bootstrap Script (Configure at First Launch): Ec2 User data

**EC2 User Data**
- It is possible to bootstrap our instances using an EC2 User Data Script
- Bootstrapping means launching commands when a Machine starts
- That script is only run-once at the instance First start
- EC2 user data is used to automate boot tasks such as:
- Installing Updates
- Installing Softwares
- Download Common files from the internet
- Anything you can think of
→ EC2 User Data Script runs with the root user

**EC2 Instance Types**

The naming convention of EC2:
Example: m5.2xlarge
m = Instance Class
5 = generation of instance
2xlarge = Size within the instance class

**Instance Types – general purpose**
- Great for a diversity of work loads such as web servers or code repositories
- Balance between
- Compute
- Memory
- Networking
- We will use t2.micro which is General purpose

**Instance Types – Compute optimised**

- Great for compute intensive tasks that require high performance processors
- Batch Processing workloads
- Media Transcoding
- High Performance web Servers
- High Performance Computing
- Scientific Modelling & machine Learning
- Dedicated Gaming Servers

**Instance Types – Memory optimised**

- Fast performance for workloads that process large data sets in memory
- Use cases:
- High performance, Relational/non relational databases
- Distributed web scale cache stores
- In-memory databases optimized for BI (Business Intelligence)
- Applications performing real-time processing of big unstructured data

**Instance Types – Storage optimised**

- Great for storage-intensive tasks that require high, sequential read and write access to large data
sets on local storage
- Use cases:
- High Frequency online transaction processing (OLTP) systems
- Relational & NoSQL databases
- Cache for in-memory databases (for example, Redis)
- Data Warehousing applications
- Distributed file systems

**What is an EBS Volume?**
- An EBS (Elastic Block Store) Volume is a network drive you
can attach to your instances while they run
- It allows your instances to persist data, even after their
termination
- They can only be mounted to one instance at a time (at the
CCP level)
- They are bound to a specific availability zone
Example: Think of them as a “network USB stick”
- Free tier: 30 GB of free EBS storage of type General Purpose
(SSD) or Magnetic per month

**EBS Volume:**
- It’s a network drive (i.e. not a physical drive)
- It uses the network to communicate the instance,
which means there might be a bit of latency
- It can be detached from an EC2 instance and attached
to another one quickly
- It’s locked to an Availability Zone (AZ)
- An EBS Volume in us-east-1a cannot be attached to
us-east-1b
- To move a volume across, you first need to snapshot it
- Have a provisioned capacity (size in GBs, and IOPS)
- You get billed for all the provisioned capacity
- You can increase the capacity of the drive over time

**EBS - Delete on Termination Attribute**
- Controls the EBS behavior when an EC2 instance terminates
- By default, the root EBS volume is deleted (attribute
enabled)
- By default, any other attached EBS volume is not
deleted (attribute disabled)
- This can be controlled by the AWS console / AWS CLI
- Use case: preserve root volume when instance is terminated

**EBS - Snapshots**
- Make a backup (snapshot) of your EBS volume at a point in
time
- Not necessary to detach volume to do snapshot, but
recommended
- Can copy snapshots across AZ or Region

**EBS Snapshots Features**
- EBS Snapshot Archive
- Move a Snapshot to an ”archive tier” that is 75%
cheaper
- Takes within 24 to 72 hours for restoring the archive
- Recycle Bin for EBS Snapshots
- Setup rules to retain deleted snapshots so you can
recover them after an accidental deletion
- Specify retention (from 1 day to 1 year)

**AMI Overview**
- AMI = Amazon Machine Image
- AMI are a customization of an EC2 instance
- You add your own software, configuration, operating
system, monitoring
- Faster boot / configuration time because all your
software is pre-packaged
- AMI are built for a specific region (and can be copied across
regions)
- You can launch EC2 instances from:
- A Public AMI: AWS provided
- Your own AMI: you make and maintain them yourself
- An AWS Marketplace AMI: an AMI someone else made
(and potentially sells)

**AMI Process:**
- Start an EC2 instance and customize it
- Stop the instance (for data integrity)
- Build an AMI – this will also create EBS snapshots
- Launch instances from other AMIs

































</details>
