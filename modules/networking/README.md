## Requirements

No requirements.

## Providers

The following providers are used by this module:

- <a name="provider_aws"></a> [aws](#provider\_aws)

## Modules

The following Modules are called:

### <a name="module_db_sg"></a> [db\_sg](#module\_db\_sg)

Source: terraform-in-action/sg/aws

Version:

### <a name="module_lb_sg"></a> [lb\_sg](#module\_lb\_sg)

Source: terraform-in-action/sg/aws

Version:

### <a name="module_vpc"></a> [vpc](#module\_vpc)

Source: terraform-aws-modules/vpc/aws

Version: 2.64.0

### <a name="module_websvr_sg"></a> [websvr\_sg](#module\_websvr\_sg)

Source: terraform-in-action/sg/aws

Version:

## Resources

The following resources are used by this module:

- [aws_availability_zones.available](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/availability_zones) (data source)

## Required Inputs

The following input variables are required:

### <a name="input_namespace"></a> [namespace](#input\_namespace)

Description: n/a

Type: `string`

## Optional Inputs

No optional inputs.

## Outputs

The following outputs are exported:

### <a name="output_sg"></a> [sg](#output\_sg)

Description: n/a

### <a name="output_vpc"></a> [vpc](#output\_vpc)

Description: n/a
