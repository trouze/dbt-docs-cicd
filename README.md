# dbt-docs-cicd
Github Action to Generate dbt docs and push to cloud storage (GCP currently supported).
Builds dbt docs into a single .html file to prevent cross referencing errors when loading from cloud storage.
---
You'll need to define some github secrets in order for this to work successfully, along with some setup with Google cloud that you can find here: [https://github.com/google-github-actions/auth#setup](https://github.com/google-github-actions/auth#setup)