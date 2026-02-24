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
