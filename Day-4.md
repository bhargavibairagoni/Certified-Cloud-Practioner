Q1. What is an Amazon VPC?

- A) A virtual server
- B) A private network in AWS
- C) A storage service
- D) A database

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q2. What does CIDR block define in a VPC?

- A) Storage capacity
- B) CPU usage
- C) IP address range
- D) Security rules

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: C

</details>

Q3. Which component allows communication between a VPC and the internet?

- A) NAT Gateway
- B) Internet Gateway
- C) Route 53
- D) Security Group

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct Answer: B

</details>

Q4. By default, can resources in a VPC communicate with the internet?

- A) Yes, always
- B) Only if Internet Gateway is attached
- C) Only if NAT Gateway exists
- D) No, never

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>


Q5. A subnet that has a route to an Internet Gateway is called:

-  A) Private Subnet
-  B) Public Subnet
-  C) Isolated Subnet
-  D) Secure Subnet

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q6. Which component controls traffic at the subnet level?

-  A) Security Group
-  B) Network ACL
-  C) Route Table
-  D) IAM

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q7. Which component controls traffic at the instance level?

-  A) Security Group
-  B) NAT Gateway
-  C) Route Table
-  D) CIDR

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: A
</details>

Q8. A route table is used to:

-  A) Store files
-  B) Define traffic routing rules
-  C) Encrypt data
-  D) Monitor performance

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q9. What is the purpose of a NAT Gateway?

-  A) Allow public subnet access
-  B) Allow private subnet to access internet
-  C) Encrypt network traffic
-  D) Monitor traffic

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q10. Can resources in a private subnet receive inbound internet traffic directly?

- A) Yes
- B) No
- C) Only with NAT Gateway
- D) Only with Security Group

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q11. Security Groups are:

- A) Stateless
- B) Stateful
- C) Region-level
- D) Used for billing
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q12. Network ACLs are:

- A) Stateful
- B) Stateless
- C) Instance-level
- D) Used for IAM
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q13. A company wants:
Web servers accessible from internet
Database not accessible from internet
What should they use?

- A) All in public subnet
- B) Web in public subnet, DB in private subnet
- C) All in private subnet
- D) No VPC
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q14. Which combination enables high availability across Availability Zones?

- A) Single subnet
- B) Multiple subnets in different AZs
- C) One EC2 instance
- D) Single Route Table
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q15. What happens if a VPC has no Internet Gateway attached?

- A) Instances can access internet
- B) Instances cannot access internet
- C) S3 stops working
- D) Route tables fail
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q16. A company wants to restrict traffic at subnet level. Which should they use?

- A) Security Group
- B) Network ACL
- C) IAM Role
- D) Elastic IP
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q17. Which of the following is required for a public subnet?

- A) NAT Gateway
- B) Internet Gateway
- C) EBS Volume
- D) IAM Role
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q18. Which VPC component acts as a firewall for EC2 instances?

- A) Route Table
- B) NACL
- C) Security Group
- D) Internet Gateway
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q.19 You have been tasked with auditing the security of your VPC. As part of this process, you need to start by analyzing what inbound and outbound traffic is allowed on your EC2 instances. What two parts of the VPC do you need to check to accomplish this task?

- A. Network ACLs and Traffic Manager.
- B. Network ACLs and Subnets.
- C. Security Groups and Internet Gateways.
- D. Security Groups and Network ACLs.
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: D
</details>

Q.20 Which statement is true in relation to security in AWS?

- A. AWS manages everything related to EC2 operating systems.
- B. AWS customers are responsible for patching any database software running on Amazon EC2.
- C. Server side encryption is the responsibility of AWS.
- D. AWS is responsible for the security of your application.
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: B
</details>

Q.21 Amazon EC2 instances are conceptually very similar to traditional servers. However, using Amazon EC2 server instances in the same manner as traditional hardware server instances is only a starting point. What are the main benefits of using the AWS EC2 instances instead of traditional servers? (Choose TWO)

- A. Improves Fault-Tolerance.
- B. Provides your business with a seamless remote accessibility.
- C. Prevents unauthorized users from getting into your network.
- D. Provides automatic data backups.
- E. Can be scaled manually in a shorter period of time.

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: A,E
</details>

Q.22 Which statement is true regarding AWS pricing? (Choose TWO)

- A. With the AWS pay-as-you-go pricing model, you don't have to pay any upfront fee.
- B. You have no responsibility for third-party software license costs.
- C. You only pay for the individual services that you need with no long-term contracts.
- D. For some services, you have to pay a startup fee in order to get the service running.
- E. There are no reservations on AWS, you only pay for what you use.

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: A,C
</details>

Q.23 Which of the following actions may reduce Amazon EBS costs? (Choose TWO)

- A. Deleting unused buckets.
- B. Using reservations.
- C. Deleting unnecessary snapshots.
- D. Changing the type of the volume.
- E. Distributing requests to multiple volumes.

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: C, D
</details>

Q.24 What should you consider when storing data in Amazon Glacier?

- A. Amazon Glacier only accepts data in a compressed format.
- B. Glacier can only be used to store frequently accessed data and data archives.
- C. Amazon Glacier does not provide immediate retrieval of data.
- D. Attach Glacier to an EC2 Instance to be able to store data.

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct Answer: C
</details>

