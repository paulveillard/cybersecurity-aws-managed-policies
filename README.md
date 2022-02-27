# AWS Managed IAM (Identity & Access Management) Policies

> An ongoing & curated collection of awesome AWS Managed IAM software best practices and remediation techniques, libraries and frameworks, E-books and videos, Technical guidelines and important resources about AWS Identiy & Access Management (IAM) Policies.


[image](https://github.com/paulveillard/cybersecurity-aws-managed-policies/blob/main/img/aws_iam.png)


When you need to set the permissions for an identity in IAM, you must decide whether to use an AWS managed policy, a customer managed policy, or an inline policy


[AWS managed policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_managed-vs-inline.html)
An AWS managed policy is a standalone policy that is created and administered by AWS. Standalone policy means that the policy has its own Amazon Resource Name (ARN) that includes the policy name. For example, arn:aws:iam::aws:policy/IAMReadOnlyAccess is an AWS managed policy. For more information about ARNs, see IAM ARNs.

Customer managed policies
You can create standalone policies that you administer in your own AWS account, which we refer to as customer managed policies. You can then attach the policies to multiple principal entities in your AWS account. When you attach a policy to a principal entity, you give the entity the permissions that are defined in the policy.
