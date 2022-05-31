## Requirements

No requirements.

## Providers

The following providers are used by this module:

- <a name="provider_aws"></a> [aws](#provider\_aws)

- <a name="provider_cloudinit"></a> [cloudinit](#provider\_cloudinit)

## Modules

The following Modules are called:

### <a name="module_alb"></a> [alb](#module\_alb)

Source: terraform-aws-modules/alb/aws

Version: ~> 5.0

### <a name="module_iam_instance_profile"></a> [iam\_instance\_profile](#module\_iam\_instance\_profile)

Source: terraform-in-action/iip/aws

Version:

## Resources

The following resources are used by this module:

- [aws_autoscaling_group.webserver](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/autoscaling_group) (resource)
- [aws_launch_template.webserver](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/launch_template) (resource)
- [aws_ami.ubuntu](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/ami) (data source)
- [cloudinit_config.config](https://registry.terraform.io/providers/hashicorp/cloudinit/latest/docs/data-sources/config) (data source)

## Required Inputs

The following input variables are required:

### <a name="input_db_config"></a> [db\_config](#input\_db\_config)

Description: n/a

Type:

```hcl
object(
    {
      user     = string
      password = string
      database = string
      hostname = string
      port     = string
    }
  )
```

### <a name="input_namespace"></a> [namespace](#input\_namespace)

Description: n/a

Type: `string`

### <a name="input_sg"></a> [sg](#input\_sg)

Description: n/a

Type: `any`

### <a name="input_ssh_keypair"></a> [ssh\_keypair](#input\_ssh\_keypair)

Description: n/a

Type: `string`

### <a name="input_vpc"></a> [vpc](#input\_vpc)

Description: n/a

Type: `any`

## Optional Inputs

No optional inputs.

## Outputs

The following outputs are exported:

### <a name="output_lb_dns_name"></a> [lb\_dns\_name](#output\_lb\_dns\_name)

Description: n/a
