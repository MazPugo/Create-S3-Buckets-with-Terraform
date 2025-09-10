This hands-on module guides you through provisioning and managing S3 using Terraform. 
You’ll start with the basics — installing Terraform and configuring AWS credentials — then build a 
Terraform configuration that creates a secure S3 bucket with versioning and public-access protections. 
You’ll also add file uploads to the Terraform state and learn tradeoffs (why Terraform is great for stable assets, but aws s3 sync is better for large, frequently changing file sets). 
Finally, the module includes a sample GitHub Actions workflow showing how to run Terraform in CI using GitHub OIDC, so you can safely operate infrastructure in a team setting without long-lived keys.

Key takeaways:

- How to write simple, idempotent Terraform to provision S3 with secure defaults.

- When to manage objects in Terraform vs. when to offload uploads to CI.

- How to configure remote state and protect against concurrent changes.

- How to use modern CI patterns (OIDC) to avoid embedding AWS credentials.
