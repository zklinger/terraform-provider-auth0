# Auth0 Terraform Provider

This repository is a **FORK** of the archived [alexkappa/terraform-provider-auth0](https://github.com/alexkappa/terraform-provider-auth0) repo.

## Usage

**Terraform 0.13+**

Terraform 0.13 and higher uses the [Terraform Registry](https://registry.terraform.io/) to download and install providers. To install this provider, copy and paste this code into your Terraform configuration. Then, run `terraform init`.

```tf
terraform {
  required_providers {
    auth0 = {
      source  = "zklinger/legacy-auth0"
      version = "0.27.0"
    }
  }
}

provider "auth0" {}
```

```sh
$ terraform init
```
