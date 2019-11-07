# Minimal Test

This test with create a new redis instance.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| location\_id | Zone to create test instance. | string | `"us-east1-b"` | no |
| memory\_size\_gb | Memory size of test instance. | number | `"1"` | no |
| name | Name of redis instance. | string | `"test-minimal"` | no |
| project\_id | Google cloud project id to create redis instance. | string | n/a | yes |
| region | Region to create test instance. | string | `"us-east1"` | no |

## Outputs

| Name | Description |
|------|-------------|
| location\_id |  |
| memory\_size\_gb |  |
| name |  |
| output\_current\_location\_ids |  |
| output\_hosts |  |
| output\_ids |  |
| output\_regions |  |
| project\_id |  |
| region |  |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
