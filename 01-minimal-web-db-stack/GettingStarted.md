# Getting Up and Running

```bash
terraform plan --out=out.tfplan --var-file=nyc3.tfvars
terraform apply "out.tfplan"
terraform destroy  --var-file=nyc3.tfvars --yes
```
