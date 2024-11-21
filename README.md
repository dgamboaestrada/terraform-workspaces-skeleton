# Terraform workspace skeleton

## Workspaces usage
```sh
terraform workspace new qa
terraform workspace list
terraform workspace select
terraform workspace delete qa
```

## Usage
```sh
terraform workspace select qa
terraform plan  -var-file=variables/qa.tfvars
terraform apply -var-file=variables/qa.tfvars
```

## Resources:
- https://developer.hashicorp.com/terraform/language/modules/develop/structure
- https://developer.hashicorp.com/terraform/language/modules/develop/providers
- https://developer.hashicorp.com/terraform/language/modules/develop/composition
- https://developer.hashicorp.com/terraform/cli/commands/workspace/list
- https://developer.hashicorp.com/terraform/cli/commands/workspace/select
- https://developer.hashicorp.com/terraform/cli/commands/workspace/new
- https://developer.hashicorp.com/terraform/cli/commands/workspace/delete
- https://developer.hashicorp.com/terraform/cli/commands/workspace/show
