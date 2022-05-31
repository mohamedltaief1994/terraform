## Requirements

The following requirements are needed by this module:

- <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) (>= 0.15)

- <a name="requirement_aws"></a> [aws](#requirement\_aws) (~> 3.28)

- <a name="requirement_cloudinit"></a> [cloudinit](#requirement\_cloudinit) (~> 2.1)

- <a name="requirement_random"></a> [random](#requirement\_random) (~> 3.0)

## Providers

No providers.

## Modules

The following Modules are called:

### <a name="module_autoscaling"></a> [autoscaling](#module\_autoscaling)

Source: ./modules/autoscaling

Version:

### <a name="module_database"></a> [database](#module\_database)

Source: ./modules/database

Version:

### <a name="module_networking"></a> [networking](#module\_networking)

Source: ./modules/networking

Version:

## Resources

No resources.

## Required Inputs

The following input variables are required:

### <a name="input_namespace"></a> [namespace](#input\_namespace)

Description: The project namespace to use for unique resource naming

Type: `string`

## Optional Inputs

The following input variables are optional (have default values):

### <a name="input_region"></a> [region](#input\_region)

Description: AWS region

Type: `string`

Default: `"us-west-2"`

### <a name="input_ssh_keypair"></a> [ssh\_keypair](#input\_ssh\_keypair)

Description: SSH keypair to use for EC2 instance

Type: `string`

Default: `null`

## Outputs

The following outputs are exported:

### <a name="output_lb_dns_name"></a> [lb\_dns\_name](#output\_lb\_dns\_name)

Description: n/a
