<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| api\_key\_id | Spacelift API Key ID | N/A | true |
| api\_key\_secret | Spacelift API Key Secret | N/A | true |
| debug | Debug mode | false | false |
| github\_token | GitHub Token | N/A | true |
| image | Docker image | N/A | true |
| image-tag | Docker image tag | N/A | true |
| namespace | Namespace | N/A | false |
| operation | Operation (valid options - `deploy`, `destroy`) | deploy | true |
| organization | Spacelift organization name | N/A | true |
| region | AWS Region | N/A | true |
| ssm-path | SSM path for Docker image | N/A | false |
| stack | Spacelift stack name | N/A | true |
| webapp-output-name | Spacelist stack output field contains webapp host name | full\_domain | false |


## Outputs

| Name | Description |
|------|-------------|
| webapp-url | Web Application url |
<!-- markdownlint-restore -->
