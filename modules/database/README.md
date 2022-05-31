## Requirements

No requirements.

## Providers

The following providers are used by this module:

- <a name="provider_aws"></a> [aws](#provider\_aws)

- <a name="provider_random"></a> [random](#provider\_random)

## Modules

No modules.

## Resources

The following resources are used by this module:

- [aws_db_instance.database](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/db_instance) (resource)
- [random_password.password](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/password) (resource)

## Required Inputs

The following input variables are required:

### <a name="input_namespace"></a> [namespace](#input\_namespace)

Description: n/a

Type: `string`

### <a name="input_sg"></a> [sg](#input\_sg)

Description: n/a

Type: `any`

### <a name="input_vpc"></a> [vpc](#input\_vpc)

Description: n/a

Type: `any`

## Optional Inputs

No optional inputs.

## Outputs

The following outputs are exported:

### <a name="output_db_config"></a> [db\_config](#output\_db\_config)

Description: n/a
