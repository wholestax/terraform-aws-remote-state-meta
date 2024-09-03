# Remote State Meta

A Terraform module that an IAM policy that provides the permissions necessary to create and destroy Terraform remote state management using S3 in AWS.

## Usage

```hcl title="main.tf"
module "remote_state_meta" {
  source = "github.com/wholestax/terraform-aws-remote-state-meta?ref=v0.0.1"
}
```

It is intended to be use with the [remote-state-s3-backend](https://registry.terraform.io/modules/nozaq/remote-state-s3-backend/aws/latest) module. See this [blog post](https://sideprojekt.io/p/sidepjekt/blog/terraform-bootstrap-layer) for an example of how to use this module.

```hcl title="main.tf"

```

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

## Requirements

| Name                                                   | Version |
| ------------------------------------------------------ | ------- |
| <a name="requirement_aws"></a> [aws](#requirement_aws) | ~> 5.0  |

## Providers

| Name                                             | Version |
| ------------------------------------------------ | ------- |
| <a name="provider_aws"></a> [aws](#provider_aws) | ~> 5.0  |

## Modules

No modules.

## Resources

| Name                                                                                                            | Type     |
| --------------------------------------------------------------------------------------------------------------- | -------- |
| [aws_iam_policy.policy](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |

## Inputs

No inputs.

## Outputs

| Name                                                  | Description |
| ----------------------------------------------------- | ----------- |
| <a name="output_policy"></a> [policy](#output_policy) | n/a         |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

```

```
