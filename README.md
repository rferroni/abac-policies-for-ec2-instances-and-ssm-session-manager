
# ABAC policies for EC2 instances and SSM Session Manager

**Introduction:**

This workshop shows how to create and test an ABAC policy which will enable an IAM role with a principal tag to create and access EC2 instances that have matching tags. In this scenario, when a principal makes a request to AWS, their permissions are granted based on whether the principal and resource have matching tags. This identity strategy enables individuals to manage and remotely access EC2 instances based on the user attributes which they pass to AWS STS.

**Key topics include:**

* Attribute-Based Access Control (ABAC) for more dynamic policy-crafting
* Session Tags, enabling additional attributes to be passed on a session-by-session basis

**Workshop:**

AWS Worksthop Studio: https://catalog.workshops.aws/iam-abac-policies

**Solution:**

![abac-diagram](https://github.com/rferroni/abac-policies-for-ec2-instances-and-ssm-session-manager/blob/main/abac-diagram.png)

**Author:**

Rodrigo Ferroni, STAM - Security Specialist, AWS - [Linkedin](https://www.linkedin.com/in/rferroni/)
