1. Cloud Concepts, Types & Deployment Methods
Q1. A company wants to use AWS for compute resources while keeping sensitive, legacy data in its own data center. Which deployment model should they use?
A) Public Cloud
B) Private Cloud
C) Hybrid Cloud
D) Community Cloud

(Correct: C - Hybrid combines public cloud with on-premises data centers)

Q2. Which deployment model offers the highest level of control, data privacy, and security, but is not cost-efficient for rapid scaling?
A) Public Cloud
B) Private Cloud
C) Hybrid Cloud
D) Multi-cloud

(Correct: B - Private cloud is dedicated to one organization)

Q3. What is the main characteristic of the Public Cloud deployment model?
A) Infrastructure is owned by a single organization and managed on-premises.
B) Resources are shared in a multi-tenant environment managed by a third-party provider.
C) Data never leaves the company's own physical data center.
D) It is only used by government agencies.

(Correct: B - Public cloud is third-party owned, shared environment) 


Q4. Who was the primary leader and visionary behind the founding of AWS in 2003–2006?
A) Jeff Bezos
B) Werner Vogels
C) Andy Jassy
D) Matt Garman

(Correct: C - Andy Jassy, with a team of 57, created the vision)

Q5. In which year was Amazon Web Services (AWS) officially launched to the public with its first core services (S3, EC2)?
A) 2000
B) 2002
C) 2006
D) 2010

(Correct: C - 2006)

Q6. What was the primary motivation for Amazon to create AWS?
A) To compete with Microsoft Azure.
B) To turn their internal "undifferentiated heavy lifting" of infrastructure into a service for others.
C) To create a new retail website.
D) To sell hardware servers.

(Correct: B - They solved their own scaling headaches)

Q7. As of 2026, approximately how many services does AWS offer?
A) Fewer than 50
B) About 100
C) Over 200
D) Exactly 500

(Correct: C - Over 200 fully-featured services) 


Q8. What is the recommended best practice for the AWS account root user?
A) Use it for daily administrative tasks.
B) Share it with all developers for full access.
C) Delete it immediately.
D) Enable MFA and use it only for tasks requiring root privileges.

(Correct: D - Root user is too powerful for daily use)

Q9. Which IAM entity is best suited to grant temporary security credentials to an Amazon EC2 instance to allow it to access an S3 bucket?
A) IAM User
B) IAM Group
C) IAM Role
D) IAM Policy

(Correct: C - IAM Roles are for temporary access, ideal for services)

Q10. What do you call a JSON document that defines permissions, specifically "who" can access "what" resources in AWS?
A) IAM User
B) IAM Policy
C) IAM Group
D) IAM Role

(Correct: B - Policies are the rulebooks/permissions)

Q11. You have 50 developers who need the same permissions. How should you manage their access efficiently?
A) Create 50 individual IAM Users and assign policies to each.
B) Share the Root Account password.
C) Create an IAM Group, add users to it, and attach a policy to the group.
D) Create an IAM Role for each developer.

(Correct: C - Groups simplify management for multiple users) 

Q12. What is an Availability Zone (AZ) in AWS?
A) A collection of data centers in a specific geographic area (e.g., US-East).
B) One or more discrete data centers with redundant power, networking, and connectivity in an AWS Region.
C) A location to cache content closer to users to reduce latency.
D) A private connection between on-premises and AWS.

(Correct: B - AZs are physically separate data centers within a Region)

Q13. A company needs to host their application in a specific country to comply with data sovereignty regulations. Which architectural component should they select?
A) Edge Location
B) Availability Zone
C) AWS Region
D) Data Center

(Correct: C - Regions are geographic locations that allow data sovereignty)

Q14. Which component of the AWS global infrastructure is used by Amazon CloudFront to cache content closer to end-users for lower latency?
A) Data Center
B) Edge Location
C) Availability Zone
D) Region

(Correct: B - Edge locations are designed for content delivery)

Q15. What is the relationship between Regions and Availability Zones?
A) A Region is inside an Availability Zone.
B) An Availability Zone consists of multiple Regions.
C) A Region consists of two or more Availability Zones.
D) There is no relationship.

(Correct: C - Regions are composed of multiple, isolated AZs) 
