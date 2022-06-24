## Usage

Add the following step to your workflow:

```yaml
- id: create-environment
  uses: celsius-actions/create-environment
  with:
    environment-manager-endpoint: <ENVIRONMENT_MANAGER_ENDPOINT>
    name: <EVIRONMENT_NAME>
    content-directory: <PATH_TO_TF_FILES>
```
