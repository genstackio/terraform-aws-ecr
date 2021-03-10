# AWS ECR Repositories Terraform module

Terraform module which creates ecr repositories on AWS.

## Usage

```hcl
module "ecr-repositories" {
  source     = "genstackio/ecr/aws//modules/repositories"

  // ...
}
```
