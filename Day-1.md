☁️ Cloud, IAM & Global Infrastructure Practice
Q1. A company wants to use AWS for compute resources while keeping sensitive data in its own data center. Which deployment model should they use?

A) Public Cloud
B) Private Cloud
C) Hybrid Cloud
D) Community Cloud

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C) Hybrid Cloud

Explanation: A Hybrid Cloud combines on-premises infrastructure with public cloud services like AWS. It allows sensitive data to remain in the company’s data center while leveraging cloud scalability.

</details>
Q2. What is the main characteristic of the Public Cloud deployment model?

A) Infrastructure is owned by one organization.
B) Resources are shared in a multi-tenant environment managed by a third-party provider.
C) Data never leaves the company.
D) Only governments can use it.

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: B

Explanation: In a Public Cloud, infrastructure is owned and operated by providers like AWS, and resources are shared among multiple customers (multi-tenant model).

</details>
Q3. Who was the primary leader behind the creation of AWS (2003–2006)?

A) Jeff Bezos
B) Werner Vogels
C) Andy Jassy
D) Matt Garman

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C) Andy Jassy

Explanation: Andy Jassy led a small team to build AWS after Amazon realized they could offer their internal infrastructure as a service.

</details>
Q4. In which year was AWS officially launched with S3 and EC2?

A) 2000
B) 2002
C) 2006
D) 2010

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C) 2006

Explanation: AWS launched Amazon S3 and EC2 in 2006, marking the beginning of modern cloud infrastructure services.

</details>
Q5. Approximately how many services does AWS currently offer?

A) Fewer than 50
B) About 100
C) Over 200
D) Exactly 500

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C) Over 200

Explanation: AWS provides more than 200 fully featured services across compute, storage, networking, AI, analytics, and more.

</details>
🔐 IAM & Root Account
Q6. What is the recommended best practice for the AWS root account?

A) Use it daily for administration
B) Share it with developers
C) Enable MFA and use only when necessary
D) Delete it

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C

Explanation: The root account has unrestricted access. Best practice is to enable MFA and use it only for tasks that require root privileges.

</details>
Q7. What is an IAM Policy?

A) An IAM identity
B) A JSON document defining permissions
C) A group of users
D) A billing report

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: B

Explanation: IAM Policies are JSON documents that define who can access what resources and what actions they can perform.

</details>
Q8. Which IAM entity provides temporary credentials to AWS services like EC2?

A) IAM User
B) IAM Group
C) IAM Role
D) Root Account

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C

Explanation: IAM Roles provide temporary security credentials and are ideal for EC2 instances accessing other AWS services.

</details>
Q9. You have 50 developers who require the same permissions. What is the best way to manage this?

A) Create 50 root accounts
B) Attach policies individually
C) Create an IAM Group and attach a policy
D) Use shared login

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C

Explanation: IAM Groups allow you to assign policies once and manage permissions efficiently for multiple users.

</details>
🌍 Regions, AZs & Edge Locations
Q10. What is an AWS Region?

A) A single data center
B) A global caching location
C) A geographic area containing multiple Availability Zones
D) A billing zone

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C

Explanation: An AWS Region is a geographic location (e.g., US-East, Asia Pacific Mumbai) containing multiple isolated Availability Zones.

</details>
Q11. What is an Availability Zone (AZ)?

A) A caching location
B) One or more discrete data centers within a Region
C) A virtual machine
D) A firewall

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: B

Explanation: An AZ consists of one or more physically separate data centers with redundant power and networking.

</details>
Q12. Why should applications be deployed across multiple Availability Zones?

A) To reduce billing
B) To increase fault tolerance and availability
C) To reduce IAM permissions
D) To increase CPU speed

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: B

Explanation: Deploying across multiple AZs ensures that if one AZ fails, the application remains available in another AZ.

</details>
Q13. Which AWS infrastructure component is used by Amazon CloudFront to cache content closer to users?

A) Region
B) Availability Zone
C) Edge Location
D) Data Center

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C

Explanation: Edge Locations are used by CloudFront to deliver cached content with low latency.

</details>
Q14. What is the relationship between Regions and Availability Zones?

A) Region is inside an AZ
B) AZ contains Regions
C) Region contains multiple AZs
D) No relationship

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C

Explanation: Each AWS Region consists of two or more isolated Availability Zones.

</details>
Q15. What is AWS responsible for under the Shared Responsibility Model?

A) Customer data
B) OS patching in EC2
C) Physical data center security
D) IAM policies

<details> <summary><strong>Show Answer</strong></summary>

Correct Answer: C

Explanation: AWS is responsible for security OF the cloud, including physical infrastructure and data center security.

</details>
