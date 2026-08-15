# OpenTofu EC2 Deployment

## Project

Created an Amazon Linux EC2 instance using OpenTofu.

## Steps

1. Created an OpenTofu project folder in VS Code.
2. Created a `main.tf` file with AWS provider and EC2 configuration.
3. Used Amazon Linux 2023 AMI through AWS SSM Parameter Store.
4. Initialized OpenTofu using `tofu init`.
5. Validated the configuration using `tofu validate`.
6. Checked the infrastructure plan using `tofu plan`.
7. Created the EC2 instance using `tofu apply`.
8. Verified the EC2 instance in the AWS Console.

## Commands

```bash
tofu init
tofu validate
tofu plan
tofu apply
tofu destroy
```

## Key Concepts

* OpenTofu
* Infrastructure as Code (IaC)
* AWS EC2
* Amazon Linux 2023
* AWS Provider
* `main.tf`
