Q1. A company wants to use AWS for compute resources while keeping sensitive data in its own data center. Which deployment model should they use?

- A) Public Cloud
- B) Private Cloud
- C) Hybrid Cloud
- D) Community Cloud

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C) Hybrid Cloud

Explanation: A Hybrid Cloud combines public cloud services with on-premises infrastructure.

</details>

Q2. What is the main characteristic of the Public Cloud deployment model?

- A) Infrastructure is owned by one organization
- B) Resources are shared in a multi-tenant environment managed by a third-party provider
- C) Data never leaves the company
- D) Only governments can use it

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

Explanation: Public cloud resources are shared among multiple customers and managed by providers like AWS.

</details>

Q3. Who was the primary leader behind the creation of AWS (2003–2006)?

- A) Jeff Bezos
- B) Werner Vogels
- C) Andy Jassy
- D) Matt Garman

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C) Andy Jassy

Explanation: Andy Jassy led the initial AWS team.

</details>

Q4. In which year was AWS officially launched with S3 and EC2?

- A) 2000
- B) 2002
- C) 2006
- D) 2010

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C) 2006

Explanation: AWS launched S3 and EC2 in 2006.

</details>

Q5. Approximately how many services does AWS currently offer?

- A) Fewer than 50
- B) About 100
- C) Over 200
- D) Exactly 500

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C) Over 200

Explanation: AWS offers 200+ fully featured services.

</details>

Q6. What is the recommended best practice for the AWS root account?

- A) Use it daily
- B) Share it
- C) Enable MFA and use only when necessary
- D) Delete it

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

Explanation: Root account should have MFA enabled and be used only for critical tasks.

</details>

Q7. What is an IAM Policy?

- A) An IAM identity
- B) A JSON document defining permissions
- C) A group of users
- D) A billing report

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

Explanation: IAM policies define permissions using JSON format.

</details>

Q8. Which IAM entity provides temporary credentials to services like EC2?

- A) IAM User
- B) IAM Group
- C) IAM Role
- D) Root Account

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

Explanation: IAM Roles provide temporary credentials.

</details>

Q9. You have 50 developers who require the same permissions. What is the best solution?

- A) Create 50 root accounts
- B) Attach policies individually
- C) Create an IAM Group and attach a policy
- D) Share login credentials

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

Explanation: IAM Groups simplify permission management.

</details>


Q10. What is an AWS Region?

- A) A single data center
- B) A caching location
- C) A geographic area containing multiple Availability Zones
- D) A billing unit

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

Explanation: A Region contains multiple AZs within a geographic location.

</details>


Q11. What is an Availability Zone (AZ)?

- A) A caching location
- B) One or more discrete data centers within a Region
- C) A virtual machine
- D) A firewall

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

Explanation: AZs are physically separate data centers within a Region.

</details>

Q12. Why deploy applications across multiple Availability Zones?

- A) Reduce cost
- B) Increase fault tolerance and availability
- C) Reduce IAM permissions
- D) Increase CPU speed

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

Explanation: Multiple AZs improve high availability.

</details>

Q13. Which component is used by CloudFront to cache content closer to users?

- A) Region
- B) Availability Zone
- C) Edge Location
- D) Data Center

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

Explanation: Edge Locations cache content for low latency delivery.

</details>


Q14. What is the relationship between Regions and Availability Zones?

- A) Region is inside AZ
- B) AZ contains Regions
- C) Region contains multiple AZs
- D) No relationship

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

Explanation: Each Region contains multiple isolated AZs.

</details>

Q15. Under the Shared Responsibility Model, what is AWS responsible for?

- A) Customer data
- B) OS patching in EC2
- C) Physical data center security
- D) IAM policies

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

Explanation: AWS is responsible for security OF the cloud, including physical infrastructure.

</details>

Q.16 Which methods can be used by customers to interact with AWS Identity and Access Management (IAM)? (Choose TWO)

- A. AWS CLI.
- B. AWS Security Groups.
- C. AWS SDKs.
- D. AWS Network Access Control Lists.
- E. AWS CodeCommit.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: A, C

</details>

Q.17 Which of the following are types of AWS Identity and Access Management (IAM) identities? (Choose TWO)

- A. AWS Resource Groups.
- B. IAM Policies.
- C. IAM Roles.
- D. IAM Users.
- E. AWS Organizations.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct answer: C, D

</details>

Q.18 Which IAM entity can best be used to grant temporary access to your AWS resources?

- A. IAM Users.
- B. Key Pair.
- C. IAM Roles.
- D. IAM Groups.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct answer: C

</details>

Q.19 A company is seeking to better secure its AWS account from unauthorized access. Which of the below options can the customer use to achieve this goal?

- A. Restrict any API call made through SDKs or CLI.
- B. Create one IAM account for each department in the company (Development, QA, Production), and share it across all staff in that department.
- C. Require Multi-Factor Authentication (MFA) for all IAM User access.
- D. Set up two login passwords.

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct answer: C

</details>




