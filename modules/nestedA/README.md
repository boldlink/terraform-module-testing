[![License](https://img.shields.io/badge/License-Apache-blue.svg)](https://github.com/boldlink/terraform-module-testing/blob/main/LICENSE)
[![Latest Release](https://img.shields.io/github/release/boldlink/terraform-module-testing.svg)](https://github.com/boldlink/terraform-module-testing/releases/latest)
[![Build Status](https://github.com/boldlink/terraform-module-testing/actions/workflows/update.yaml/badge.svg)](https://github.com/boldlink/terraform-module-testing/actions)
[![Build Status](https://github.com/boldlink/terraform-module-testing/actions/workflows/release.yaml/badge.svg)](https://github.com/boldlink/terraform-module-testing/actions)
[![Build Status](https://github.com/boldlink/terraform-module-testing/actions/workflows/pre-commit.yaml/badge.svg)](https://github.com/boldlink/terraform-module-testing/actions)
[![Build Status](https://github.com/boldlink/terraform-module-testing/actions/workflows/pr-labeler.yaml/badge.svg)](https://github.com/boldlink/terraform-module-testing/actions)
[![Build Status](https://github.com/boldlink/terraform-module-testing/actions/workflows/module-examples-tests.yaml/badge.svg)](https://github.com/boldlink/terraform-module-testing/actions)
[![Build Status](https://github.com/boldlink/terraform-module-testing/actions/workflows/checkov.yaml/badge.svg)](https://github.com/boldlink/terraform-module-testing/actions)
[![Build Status](https://github.com/boldlink/terraform-module-testing/actions/workflows/auto-merge.yaml/badge.svg)](https://github.com/boldlink/terraform-module-testing/actions)
[![Build Status](https://github.com/boldlink/terraform-module-testing/actions/workflows/auto-badge.yaml/badge.svg)](https://github.com/boldlink/terraform-module-testing/actions)

[<img src="https://avatars.githubusercontent.com/u/25388280?s=200&v=4" width="96"/>](https://boldlink.io)

# Terraform  module \<PROVIDER>-\<MODULE>\<NESTED_MODULE> Terraform module

\<Description>

This terraform module lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum ipsum lorem ipsum ipsum lorem ipsum ipsum lorem ipsum.

Examples available [`here`]github.com/boldlink/<REPO_NAME>//tree/main/examples)

## Usage
*NOTE*: These examples use the latest version of this module

```console
module "miniumum" {
  source  = "boldlink/<module_name>/<provider>//modules/<nested_name>"
  version = "x.x.x"
  # insert the minimum required variables here
  ...
}
```
## Documentation

[Amazon Documentation](https://link)

[Terraform module documentation](https://link)

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.14.11 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | >= 4.20.0 |

## Providers

No providers.

## Modules

No modules.

## Resources

No resources.

## Inputs

No inputs.

## Outputs

No outputs.
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->

## Third party software
This repository uses third party software:
* [pre-commit](https://pre-commit.com/) - Used to help ensure code and documentation consistency
  * Install with `brew install pre-commit`
  * Manually use with `pre-commit run`
* [terraform 0.14.11](https://releases.hashicorp.com/terraform/0.14.11/) For backwards compatibility we are using version 0.14.11 for testing making this the min version tested and without issues with terraform-docs.
* [terraform-docs](https://github.com/segmentio/terraform-docs) - Used to generate the [Inputs](#Inputs) and [Outputs](#Outputs) sections
  * Install with `brew install terraform-docs`
  * Manually use via pre-commit
* [tflint](https://github.com/terraform-linters/tflint) - Used to lint the Terraform code
  * Install with `brew install tflint`
  * Manually use via pre-commit

#### BOLDLink-SIG 2022
