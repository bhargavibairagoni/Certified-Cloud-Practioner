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

- **Hands On**
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

- **Hands On**

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

- **Note: If you lose your device, your AWS account will be locked permanently.**

- **IAM Access Keys, CLI & SDK:**
- **How can users access AWS?**
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
- **Another Way is AWS CloudShell within AWS Console
-- Hands On —--**

- **IAM Roles for Services:**
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
- **—-- Hands On —--
IAM Security Tools:
- IAM Credentials Report (Account Level)**
- A report that lists all your account’s users and the status of
their various credentials
**IAM Access Advisor (User Level)**
- Access Advisor shows the service permissions granted to a
user and when the services were last accused.
- Using this, We can revise our policies

- **—-- Hands On —--**
- **IAM Best Practices & Guidelines**
  
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
- Example: m5.2xlarge
- m = Instance Class
- 5 = generation of instance
- 2xlarge = Size within the instance class

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


**Scalability & High Availability:**
-	Scalability means that an application / system can handle greater loads by adapting.
-	There are two kinds of scalability:
-	Vertical Scalability
-	Horizontal Scalability (= elasticity)
-	Scalability is linked but different to High Availability

**Vertical Scalability:**
-	Vertical Scalability means increasing the size of the instance
-	For example, your application runs on a t2.micro
-	Scaling that application vertically means running it on a t2.large
-	Vertical scalability is very common for non distributed systems, such as a database.

**Horizontal Scalability:**
-	Horizontal Scalability means increasing the number of instances / systems for your application
-	Horizontal scaling implies distributed systems.
-	This is very common for web applications / modern applications
-	It’s easy to horizontally scale thanks the cloud offerings such as Amazon EC2

**High Availability:**
-	High Availability usually goes hand in hand with horizontal scaling
-	High availability means running your application / system in at least 2 Availability Zones
-	The goal of high availability is to survive a data center loss
(disaster)

**High Availability & Scaling for EC2**
-	Vertical Scaling: Increase instance size (= scale up / down)
-	From: t2.nano - 0.5G of RAM, 1 vCPU
-	To: u-12tb1.metal – 12.3 TB of RAM, 448 vCPUs
 
-	High Availability: Run instances for the same application across multi AZ
-	Auto Scaling Group multi AZ
-	Load Balancer multi AZ

**Load Balancing:**
-	Load balancers are servers that forward internet traffic to multiple servers (EC2 Instances) downstream

**Why use a Load Balancer?**
-	Spread load across multiple downstream instances
-	Expose a single point of access (DNS) to your application
-	Seamlessly handle failures of downstream instances
-	Do regular health checks to your instances
-	Provide SSL termination (HTTPS) for your websites
-	High availability across zone


**Why Use an Elastic Load Balancer?**
-	An ELB (Elastic Load Balancer) is a managed load balancer
-	AWS guarantees that it will be working
-	AWS takes care of upgrades, maintenance, high availability
-	AWS provides only a few configuration knobs
-	It costs less to setup your own load balancer but it will be a lot more effort on your end (maintenance, integrations)
-	4 kinds of load balancers offered by AWS
-	Application Load Balancer (HTTP / HTTPS only) – Layer 7
-	Network Load Balancer (ultra-high performance, allows for TCP) – Layer 4
-	Gateway Load Balancer – Layer 3
-	Classic Load Balancer (retired in 2023) – Layer 4 & 7


**Auto Scaling Group:**
-	In real-life, the load on your websites and application can change
-	In the cloud, you can create and get rid of servers very quickly
-	The goal of an Auto Scaling Group (ASG) is to:
-	Scale out (add EC2 instances) to match an increased load
-	Scale in (remove EC2 instances) to match a decreased load
-	Ensure we have a minimum and a maximum number of machines running
-	Automatically register new instances to a load balancer
-	Replace unhealthy instances
-	Cost Savings: only run at an optimal capacity (principle of the cloud)

**ASG - Scaling Strategies**
- **Manual Scaling**: Update the size of an ASG manually
- **Dynamic Scaling**: Respond to Changing Demand
Simple/Step Scaling
-	When a CloudWatch alarm is triggered (example CPU > 70%), then add 2 units
-	When a CloudWatch alarm is triggered (example CPU <
30%), then remove 1

**Target Tracking Scaling**
-	Example: I want the average ASG CPU to stay at around 40%
- **Scheduled Scaling:**
-	Anticipate a scaling based on known usage patterns
-	Example: increase the min. capacity to 10 at 5 pm on Fridays

**Predictive Scaling:**
-	Uses Machine Learning to predict future traffic ahead of time
-	Automatically provisions the right number of EC2 instances in advance
-	Useful when your load has predictable time - based patterns Summary:
-	High Availability vs Scalability (vertical and horizontal) vs Elasticity vs Agility in the Cloud
-	Elastic Load Balancers (ELB)
-	Distribute traffic across backend EC2 instances, can be Multi-AZ • Supports health checks
-	4 types: Classic (old), Application (HTTP – L7), Network
(TCP – L4), Gateway (L3)
-	Auto Scaling Groups (ASG)
-	Implement Elasticity for your application, across multiple AZ
-	Scale EC2 instances based on the demand on your
-	Integrated with ELB system, replace unhealthy.



</details>



<details> <summary><strong>▶ DAY-4 </strong></summary>


**Amazon S3**
- Amazon S3 is one of the main building blocks of AWS
- It’s advertised as ”infinitely scaling” storage
- Many websites use Amazon S3 as a backbone
- Many AWS services use Amazon S3 as an integration as well

**Use Cases:**
- Backup and storage
- Disaster Recovery
- Archive
- Hybrid Cloud storage
- Application hosting
- Media hosting
- Data lakes G big data analytics
- Software delivery
- Static website

**Buckets:**
- Amazon S3 allows people to store objects (files) in “buckets”(directories)
- Buckets must have a globally unique name (across all regions all accounts)
- Buckets are defined at the region level
- S3 looks like a global service but buckets are created in a region
  
**Objects**
- Objects (files) have a Key
- Just keys with very long names that contain slashes (“/”)
- Object values are the content of the body:
- Max. Object Size is 5TB (5000GB)
- If uploading more than 5GB, must use “multi-part upload”
- Metadata (list of text key / value pairs – system or user metadata)
- Tags (Unicode key / value pair – up to 10) – useful for security/ lifecycle
- Version ID (if versioning is enabled

**Security of S3**
- **User-Based:**
- IAM Policies – which API calls should be allowed for a specific user from IAM
**Resource-Based:**
- Bucket Policies – bucket wide rules from the S3 console - allows cross account
- Object Access Control List (ACL) – finer grain (can be disabled)
- Bucket Access Control List (ACL) – less common (can be disabled)
- **Note: an IAM principal can access an S3 object if**
-  The user IAM permissions ALLOW it OR the resource policy
-  ALLOWS it
- AND there’s no explicit DENY
**Encryption:** encrypt objects in Amazon S3 using encryption keys

**Bucket Policies:**
- JSON based policies:
- Resources: buckets and objects
- Effect: Allow / Deny
- Actions: Set of API to Allow or Deny
- Principal: The account or user to apply the policy to

**Use S3 bucket for policy to:**
⦁ Grant public access to the bucket
⦁ Force objects to be encrypted at upload
⦁ Grant access to another account (Cross Account)
- {
- "Version": "2012-10-17",
- "Statement": [
- {
- "Sid": "publicRead",
- "Effect": "Allow",
- "principal": "*",
- "Action": [
- "s3:GetObject"
- ],
- "resource": [
- "arn:aws:s3:::samplebucket/*"
- ]
- }
- ]
- }

**Static Website Hosting:**
- S3 can host static websites and have them accessible on the Internet
- If you get a 403 Forbidden error, make sure the bucket policy allows public reads

**Task:**
- Install Visual Studio code
- Create a file “index.html” and “!” and press tab
- Add some content and images in a folder
- Upload all the files in the folder to S3
- Enable static website hosting in Bucket Properties

**Versioning:**
- You can version your files in Amazon S3
- It is enabled at the bucket level
- Same key overwrite will change the “version”: 1, 2, 3….
- It is best practice to version your buckets
- Protect against unintended deletes (ability to restore a version) • Easy roll back to previous version

**Note:**
- Any file that is not versioned prior to enabling versioning will have version “null”
- Suspending versioning does not delete the previous versions

**Replication:**
- Must enable Versioning in source and destination buckets
- Cross-Region Replication (CRR)
- Same-Region Replication (SRR)
- Buckets can be in different AWS accounts
- Copying is asynchronous
- Must give proper IAM permissions to S3

**Use cases:**
- CRR – compliance, lower latency access, replication across accounts
- SRR – log aggregation, live replication between production and test account S3 Storage Classes
- Amazon S3 Standard - General Purpose
- Amazon S3 Standard-Infrequent Access (IA)
- Amazon S3 One Zone-Infrequent Access
- Amazon S3 Glacier Instant Retrieval
- Amazon S3 Glacier Flexible Retrieval
- Amazon S3 Glacier Deep Archive
- Amazon S3 Intelligent Tiering
- Can move between classes manually or using S3 Lifecycle configurations

**S3 Durability & Availability**
- **Durability:**
- High durability (99.999999999%, 11 9’s) of objects across multiple AZ
- If you store 10,000,000 objects with Amazon S3, you can on average expect to incur a loss of a single object once every 10,000 years
- Same for all storage classes

**Availability:**
- Measures how readily available a service is
- Varies depending on storage class
- Example: S3 standard has 99.99% availability = not available 53 minutes a year

**S3 Standard - General Purpose**
- 99.99% Availability
- Used for frequently accessed data
- Low latency and high throughput
- Sustain 2 concurrent facility failures
**Use Cases:** Big Data analytics, mobile G gaming applications, content distribution…

**S3 Storage Classes - Infrequent Access**
- For data that is less frequently accessed, but requires rapid access when needed
- Lower cost than S3 Standard

**Amazon S3 Standard-Infrequent Access (S3 Standard-IA)**
- 99.9% Availability
- Use cases: Disaster Recovery, backups

**Amazon S3 One Zone-Infrequent Access (S3 One Zone-IA)**
- High durability (99.999999999%) in a single AZ; data lost when AZ is destroyed
- 99.5% Availability
- Use Cases: Storing secondary backup copies of on-premise data, or data you can recreate

**Amazon S3 Glacier Storage Classes**
- Low-cost object storage meant for archiving / backup
- Pricing: price for storage + object retrieval cost

**Amazon S3 Glacier Instant Retrieval**
- Millisecond retrieval, great for data accessed once a quarter
- Minimum storage duration of 90 days

**Amazon S3 Glacier Flexible Retrieval (formerly Amazon S3 Glacier):**
- Expedited (1 to 5 minutes), Standard (3 to 5 hours), Bulk (5 to 12 hours) – free
- Minimum storage duration of 90 days

**Amazon S3 Glacier Deep Archive **
– for long term storage:
- Standard (12 hours), Bulk (48 hours)
- Minimum storage duration of 180 days

**S3 Intelligent-Tiering**
- Small monthly monitoring and auto-tiering fee
- Moves objects automatically between Access Tiers based on usage
- There are no retrieval charges in S3 Intelligent-Tiering
- Frequent Access tier (automatic): default tier
- Infrequent Access tier (automatic): objects not accessed for 30 days

**Archive Instant Access tier (automatic)**: objects not accessed for 90 days
- Archive Access tier (optional): configurable from 90 days to 700+ days
- Deep Archive Access tier (optional): config. from 180 days to 700+ days

**Shared Responsibility Model for S3:**
- **AWS** 
1. Infrastructure (global security, durability, availability, sustain concurrent loss of data in two facilities)
2. Configuration and vulnerability analysis
3. Compliance validation

**Customer**
1. S3 Versioning
2. S3 Bucket Policies
3. S3 Replication Setup
4. Logging and Monitoring
5. S3 Storage Classes
6. Data encryption at rest and in transit

**AWS Snow Family**
- Highly-secure, portable devices to collect and process data at the edge, and migrate data into and out of AWS

**Data Migration:**
- Snowcone
- Snowball Edge
- Snowmobile

**Edge Computing**
- Snowcone
- Snowball Edge

**Challenges for Data Migrations:**
- Limited Connectivity
- Limited Bandwidth
- High Network Cost
- Shared Bandwidth (Can’t maximize the line)
- Connection Stability

**Data Migration with Snow Family:**
- Offline devices to perform data migrations If it takes more than a week to transfer over the network, use Snowball devices!

**Snowball Edge (for data transfers)**
- Physical data transport solution: move TBs or PBs of data in or out of AWS
- Alternative to moving data over the network (and paying network fees)
- Pay per data transfer job
- Provide block storage and Amazon S3 -compatible object storage

**Snowball Edge Storage Optimized**
- 80 TB of HDD capacity for block volume and S3 compatible object storage

**Snowball Edge Compute Optimized**
- 42 TB of HDD or 28TB NVMe capacity for block volume and S3 compatible object storage
- Use cases: large data cloud migrations, DC decommission, disaster recovery

**AWS Snowcone & Snowcone SSD:**
- Small, portable computing, anywhere, rugged G secure, withstands harsh environments
- Light (4.5 pounds, 2.1 kg)
- Device used for edge computing, storage, and data transfer
- Snowcone – 8 TB of HDD Storage
- Snowcone SSD – 14 TB of SSD Storage
- Use Snowcone where Snowball does not fit (space - constrained environment)
- Must provide your own battery / cables
- Can be sent back to AWS offline, or connect it to internet and use AWS DataSync to send data
  
**AWS Snowmobile**
- Transfer exabytes of data (1 EB = 1,000 PB = 1,000,000 TBs)
- Each Snowmobile has 100 PB of capacity (use multiple in parallel)
**High security:** temperature controlled, GPS, 24/7 video surveillance
- Better than Snowball if you transfer more than 10 PB

**Snow Family Usage Process:**
- Request Snowball devices from the AWS console for delivery
- Install the snowball client / AWS OpsHub on your servers
- Connect the snowball to your servers and copy files using the client
- Ship back the device when you’re done (goes to the right AWS facility)
- Data will be loaded into an S3 bucket
- Snowball is completely wiped

**What is Edge Computing:**
- Process data while it’s being created on an edge location
- These locations may have
- Limited / no internet access
- Limited / no easy access to computing power
- We setup a Snowball Edge / Snowcone device to do

**edge computing**
- Use cases of Edge Computing:
- Preprocess data
- Machine learning at the edge
- Transcoding media streams
- Eventually (if need be) we can ship back the device to AWS(for transferring data for example)

**Snow Family - Edge Computing**
- Snowcone G Snowcone SSD (smaller)
- 2 CPUs, 4 GB of memory, wired or wireless access
- USB-C power using a cord or the optional battery

**Snowball Edge – Compute Optimized**
- 104 vCPUs, 416 GiB of RAM
- Optional GPU (useful for video processing or machine learning)
- 28TB NVMe or 42TB HDD usable storage
- Storage Clustering available (up to 16 nodes)

**Snowball Edge – Storage Optimized**
- Up to 40 vCPUs, 80 GiB of RAM, 80 TB storage
- All: Can run EC2 Instances G AWS Lambda functions (using AWS IoT Greengrass)
- Long-term deployment options: 1 and 3 years discounted pricing

**AWS OpsHub**
- Historically, to use Snow Family devices, you needed a CLI (Command Line Interface tool)
- Today, you can use AWS OpsHub (a software you install on your computer / laptop) to manage your Snow Family Device
- Unlocking and configuring single or clustered devices
- Transferring files
- Launching and managing instances running on Snow Family Devices
- Monitor device metrics (storage capacity, active instances on your device)
- Launch compatible AWS services on your devices (ex: Amazon EC2 instances, AWS DataSync, Network File System (NFS)

**AWS Storage Cloud Native Options:**
- Block → Amazon EBS G EC2 Instance Store
- File → Amazon EFS
- Object → Amazon S3 G Glacier


</details>

------------------------------------------------------------------------------------------------------------------------------------

