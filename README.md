# Terraform workspace skeleton

## Workspaces usage
```sh
terraform workspace new qa
terraform workspace list
terraform workspace select qa
terraform workspace delete qa
```

## Usage
```sh
terraform workspace select qa
terraform plan  -var-file=variables/qa.tfvars
terraform apply -var-file=variables/qa.tfvars
```
