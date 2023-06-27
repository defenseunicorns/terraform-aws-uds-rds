# AWS RDS Module

This repository contains Terraform configuration files that create an RDS (Relational Database Service) instance. This module also creates a KMS (Key Management Service) key and uses it to encrypt and decrypt the backups of the RDS instance.

## Examples

To view examples for how you can leverage this RDS Module, please see the [examples](https://github.com/defenseunicorns/terraform-aws-uds-rds/tree/main/examples) directory.
<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.0.0 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | >= 4.45 |
| <a name="requirement_random"></a> [random](#requirement\_random) | >= 3.1 |

## Providers

No providers.

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_db"></a> [db](#module\_db) | git::https://github.com/terraform-aws-modules/terraform-aws-rds.git | v5.9.0 |
| <a name="module_security_group"></a> [security\_group](#module\_security\_group) | terraform-aws-modules/security-group/aws | 5.1.0 |

## Resources

No resources.

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
