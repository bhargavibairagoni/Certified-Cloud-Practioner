Q1. What is the main purpose of Amazon EC2?
- A) Store files
- B) Run virtual servers in the cloud
- C) Manage DNS
- D) Monitor applications

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q2. What does “Elastic” mean in EC2?
- A) Automatic backups
- B) Flexible scaling of resources
- C) Free storage
- D) Static IP

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q3. Which of the following is part of an EC2 instance?
- A) CPU
- B) RAM
- C) Storage
- D) All of the above

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: D

</details>

Q4. An EC2 instance is best described as:
- A) A physical server owned by customer
- B) A virtual server running in AWS
- C) A database service
- D) A networking tool

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q5. What is an AMI primarily used for?
- A) Monitoring instance performance
- B) Creating EC2 instances
- C) Storing backups
- D) Assigning IP addresses

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q6. An AMI contains:
- A) Operating System
- B) Pre-installed software
- C) Configuration settings
- D) All of the above

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: D

</details>

Q7. Which instance type is best for a database requiring high memory?
- A) Compute Optimized
- B) Memory Optimized
- C) Storage Optimized
- D) GPU

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q9. What happens to EBS data when an EC2 instance is stopped?
- A) Data is deleted
- B) Data remains
- C) Data is moved to S3
- D) Data becomes public

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q10. EBS is best described as:
- A) Object storage
- B) Block storage attached to EC2
- C) CDN
- D) Firewall

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q11. What is the purpose of a Security Group?
- A) Backup control
- B) Firewall for EC2
- C) Monitoring
- D) Billing

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q12. Security Groups operate at which level?
- A) Application
- B) Instance level
- C) Region level
- D) Account level

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q13. What is a Key Pair used for?
- A) Encrypting S3
- B) Logging into EC2 securely
- C) DNS management
- D) Auto scaling

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q14. If you lose your private key for EC2 login, what happens?
- A) AWS sends new one automatically
- B) You cannot SSH into the instance
- C) Instance deletes
- D) Security group resets

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q15. What is an Elastic IP?
- A) Temporary IP
- B) Static public IP address
- C) Internal IP
- D) DNS service

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q16. Why use Elastic IP?
- A) For permanent public access to EC2
- B) To increase CPU
- C) To improve storage
- D) To reduce RAM

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: A

</details>

Q18. What is the main benefit of Auto Scaling Group?
- A) Fixed number of instances
- B) Automatically adjusts number of EC2 instances
- C) Reduces storage cost
- D) Assigns Elastic IP

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>


Q.19 A company is using EC2 Instances to run their e-commerce site on the AWS platform. If the site becomes unavailable, the company will lose a significant amount of money for each minute the site is unavailable. Which design principle should the company use to minimize the risk of an outage?

- A. Least Privilege.
- B. Pilot Light.
- C. Fault Tolerance.
- D. Multi-threading.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

</details>

Q.20 You decide to buy a reserved instance for a term of one year. Which option provides the largest total discount?

- A. All up-front reservation.
- B. All reserved instance payment options provide the same discount level.
- C. Partial up-front reservation.
- D. No up-front reservation.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: A

</details>

Q.21 An AWS customer has used one Amazon Linux instance for 2 hours, 5 minutes and 9 seconds, and one CentOS instance for 4 hours, 23 minutes and 7 seconds. How much time will the customer be billed for?

- A. 3 hours for the Linux instance and 5 hours for the CentOS instance.
- B. 2 hours, 5 minutes and 9 seconds for the Linux instance and 4 hours, 23 minutes and 7 seconds for the CentOS instance.
- C. 2 hours, 5 minutes and 9 seconds for the Linux instance and 5 hours for the CentOS instance.
- D. 3 hours for the Linux instance and 4 hours, 23 minutes and 7 seconds for the CentOS instance.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C
Explanation:

Pricing is per instance-hour consumed for each instance, from the time an instance is launched until it is terminated or stopped.
Each partial instance-hour consumed will be billed per-second for Linux, Windows, Windows with SQL Enterprise, Windows with SQL Standard, and Windows with SQL Web Instances, and as a full hour for all other instance types.

</details>

Q.22 A company has a web application that is hosted on a single EC2 instance and is approaching 100 percent CPU Utilization during peak loads. Rather than scaling the server vertically, the company has decided to deploy three Amazon EC2 instances in parallel and to distribute traffic across the three servers. What AWS Service should the company use to distribute the traffic evenly?

- A. AWS Global Accelerator.
- B. AWS Application Load Balancer (ALB).
- C. Amazon CloudFront.
- D. Transit VPC.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q.23 A company is seeking to better secure its AWS account from unauthorized access. Which of the below options can the customer use to achieve this goal?

- A. Restrict any API call made through SDKs or CLI.
- B. Create one IAM account for each department in the company (Development, QA, Production), and share it across all staff in that department.
- C. Require Multi-Factor Authentication (MFA) for all IAM User access.
- D. Set up two login passwords.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

</details>

Q.24 What are the advantages of using Auto Scaling Groups for EC2 instances?

- A. Auto Scaling Groups caches the most recent responses at global edge locations to reduce latency and improve performance.
- B. Auto Scaling Groups scales EC2 instances in multiple Availability Zones to increase application availability and fault tolerance.
- C. Auto Scaling Groups scales EC2 instances across multiple regions to reduce latency for global users.
- D. Auto Scaling Groups distributes application traffic across multiple Availability Zones to enhance performance.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q.25 Which of the following is a type of MFA device that customers can use to protect their AWS resources?

- A. AWS CloudHSM.
- B. U2F Security Key.
- C. AWS Access Keys.
- D. AWS Key Pair.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q.26 Which of the following is NOT a factor when estimating the costs of Amazon EC2? (Choose TWO)

- A. The amount of time the instances will be running.
- B. Number of security groups.
- C. Allocated Elastic IP Addresses.
- D. Number of Hosted Zones.
- E. Number of instances.
<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B, D

</details>

Q.27 Which of the below options is a best practice for making your application on AWS highly available?

- A. Deploy the application to at least two Availability Zones.
- B. Use Elastic Load Balancing (ELB) across multiple AWS Regions.
- C. Deploy the application code on at least two servers in the same Availability Zone.
- D. Rewrite the application code to handle all incoming requests.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: A

</details>

Q.28 A company is migrating a web application to AWS. The application’s compute capacity is continually utilized throughout the year. Which of the below options offers the company the most cost-effective solution?

- A. On-demand Instances.
- B. Dedicated Hosts.
- C. Spot Instances.
- D. Reserved Instances.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: D

</details>

Q.29 When granting permissions to applications running on Amazon EC2 instances, which of the following is considered best practice?

- A. Generate new IAM access keys every time you delegate permissions.
- B. Store the required AWS credentials directly within the application code.
- C. Use temporary security credentials (IAM roles) instead of long-term access keys.
- D. Do nothing; Applications that run on Amazon EC2 instances do not need permission to interact with other AWS services or resources.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

</details>

Q.30 According to best practices, which of the below options is best suited for processing a large number of binary files?

- A. Vertically scaling EC2 instances.
- B. Running RDS instances in parallel.
- C. Vertically scaling RDS instances.
- D. Running EC2 instances in parallel.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: D

</details>

Q.31 What should you do if you see resources, which you don’t remember creating, in the AWS Management Console? (Choose TWO)

- A. Stop all running services and open an investigation.
- B. Give your root account password to AWS Support so that they can assist in troubleshooting and securing the account.
- C. Check the AWS CloudTrail logs and delete all IAM users that have access to your resources.
- D. Open an investigation and delete any potentially compromised IAM users.
- E. Change your AWS root account password and the passwords of any IAM users.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: D, E

</details>

Q.32 A new service using AWS must be highly available. Yet, due to regulatory requirements, all of its Amazon EC2 instances must be located in a single geographic area.
According to best practices, to meet these requirements, the EC2 instances must be placed in at least two:

- A. AWS Regions
- B. Availability Zones
- C. subnets
- D. placement groups

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: A

</details>
