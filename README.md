# Remote State Meta

A Terraform module that an IAM policy that provides the permissions necessary to create and destroy Terraform remote state management using S3 in AWS.

## Usage

```hcl title="main.tf"
module "remote_state_meta" {
  source = "github.com/wholestax/terraform-aws-remote-state-meta?ref=v0.0.1"
}
```
