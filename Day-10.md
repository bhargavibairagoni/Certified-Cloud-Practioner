Q1. A company wants to automatically create AWS resources such as EC2 instances and S3 buckets using a template instead of manually creating them in the console. Which AWS service should they use?

- A. AWS Elastic Beanstalk
- B. AWS CloudFormation
- C. AWS Lambda
- D. Amazon ECS

<details> <summary><strong>▶ Show Answer</strong></summary>

Correct answer: B
Explanation: CloudFormation allows infrastructure to be created and managed using templates.
</details>

Q2. A developer deploys infrastructure using a CloudFormation template. What is the collection of AWS resources created from that template called?

- A. Stack
- B. Bucket
- C. Deployment Group
- D. Container

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer: A
Explanation: When a CloudFormation template is executed, it creates a Stack.
</details>

Q3. A company wants to deploy the same infrastructure template across multiple AWS accounts and multiple regions. Which CloudFormation feature should they use?

A. Change Sets
B. StackSets
C. Drift Detection
D. Nested Stacks

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer: B
Explanation: StackSets allow deployment of stacks across multiple accounts and regions.
</details>

Q4. A DevOps engineer wants to preview how infrastructure will change before applying a CloudFormation update. Which feature should they use?

A. Drift Detection
B. Change Sets
C. StackSets
D. Nested Stacks

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer: B
Explanation: Change Sets allow you to preview modifications before updating a stack.
</details>

Q5. A company wants to detect whether the actual AWS resources differ from the configuration defined in a CloudFormation template. Which feature should they use?

A. Drift Detection
B. Stack Policy
C. Change Sets
D. StackSets

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer: A
Explanation: Drift Detection identifies differences between stack configuration and actual resources.
</details>

Q6. A developer wants to create multiple related CloudFormation templates and combine them into a single stack. Which CloudFormation feature should they use?

A. Nested Stacks
B. StackSets
C. Drift Detection
D. Lambda

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer: A
Explanation: Nested stacks allow multiple templates to be organized and reused..
</details>

Q7. A company wants to ensure that critical resources in a CloudFormation stack cannot be accidentally deleted during updates. Which feature should they use?

A. Stack Policy
B. Change Sets
C. Drift Detection
D. StackSets

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer:A
Explanation: Stack policies prevent modifications to specific resources.
</details>

Q8. A company has manually created several AWS resources and now wants to convert them into Infrastructure as Code templates automatically. Which CloudFormation feature can help?

A. Change Sets
B. Drift Detection
C. IaC Generator
D. Nested Stacks

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer:C
Explanation: IaC Generator can generate templates for existing infrastructure.
</details>

Q9. A developer deletes a CloudFormation stack. What happens to the resources created by that stack?

A. They remain active
B. They are deleted automatically
C. They move to another stack
D. They are archived

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer:B
Explanation: Deleting a stack deletes its resources unless retention policies are applied.
</details>

Q10. A company wants to reuse common infrastructure templates such as VPC configurations across multiple projects. What is the best CloudFormation approach?

A. Nested Stacks
B. StackSets
C. Drift Detection
D. Lambda

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer:A
Explanation: Nested stacks allow reuse of infrastructure templates.
</details>

Q11. A DevOps engineer wants to update a CloudFormation stack without causing downtime for running applications. Which approach should they use?

A. Stack update
B. Stack deletion
C. Manual resource modification
D. CloudWatch alarms
 
<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer:A
Explanation: Updating a stack allows resources to be modified safely.
</details>

Q12. Which format can be used to write CloudFormation templates?

A. JSON or YAML
B. Python only
C. Java only
D. Bash scripts

<details> <summary><strong>▶ Show Answer</strong></summary>
Correct answer:A
Explanation: CloudFormation templates are written in JSON or YAML.
</details>










