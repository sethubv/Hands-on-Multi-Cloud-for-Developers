![HashiCorp's Terraform](https://cultivatedops-static.s3.amazonaws.com/thirdparty/terraform/logo-50.png)

This repository is a [Terraform](https://terraform.io/) Module for managing Cisco CSR VPN resources

The module creates a Cisco CSR VPN router on AWS Infrastructure

# Usage

Add the module to your Terraform resources like so:

```
module "cisco-csr-aws" {
  source = "./terraform-module-cisco-csr-aws"
  arg1 = "foo"
}
```

Then, load the module using `terraform get`.

# Options

This module supports a number of configuration options:

| option    | description |
|-----------|-|
| `arg1`    | argument #1 |

# Outputs

This module supports a number of outputs:

| output   | description |
|----------|-|
| `output` | value of the `resource.name.attr` resource  |

[//]: # (This file was generated by `yo terraform-module`)
[//]: # (using template v1.0.0, hash: 648cc358532fdbb19c1d48362791f61b))
