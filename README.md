# terraform-aws-iam-role-datadog-integration
Terraform module which creates an IAM Role for DataDog integration.

Usage
-----

```hcl
module "aws-datadog-integration-role" {
  source  = "github.com/traveloka/terraform-aws-iam-role-datadog-integration.git?ref=v0.1.0"
  version = "0.1.0"

  external_id = "abcdef0123456789abcdef0123456789"
}
```

Authors
-------

- [Ronny Kaluge](https://github.com/ronny-kaluge)

License
-------

Apache 2 Licensed. See LICENSE for full details.
