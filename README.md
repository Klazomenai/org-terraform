## Management as Code
The entry point into the organisational strucutre defined in Terraform.

## Structure
`.tf` files in this repo shall contain `module`s, `source`s, or `variable`s only! Or I stop entering in `4 8 15 16 23 42`.

## Terraform
```sh
terraform init
```

## Notes
Looks like `.terraform` needs to be deleted when external sources get updated, `terraform init` on its own, does not detect changes.
