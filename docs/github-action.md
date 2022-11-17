<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| api\_key\_id | Spacelift API key id | N/A | true |
| api\_key\_secret | Spacelift API key secret | N/A | true |
| debug | Debug mode | false | false |
| github\_token | GitHub Token | N/A | true |
| image | Docker image | N/A | true |
| image-tag | Docker image tag | N/A | true |
| namespace | Namespace | N/A | false |
| operation | Operation with helmfiles. (valid options - `deploy`, `destroy`) | deploy | true |
| organization | Spacelift organization | N/A | true |
| region | AWS Region | N/A | true |
| ssm-path | SSM path | N/A | false |
| stack | Name | N/A | true |


## Outputs

| Name | Description |
|------|-------------|
| webapp-url | Web Application url |
<!-- markdownlint-restore -->
