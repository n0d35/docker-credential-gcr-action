[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-908a85?logo=gitpod)](https://gitpod.io/#https://github.com/n0d35/docker-credential-gcr-action)

# Docker Credential GCR Action

Action for configuring Docker to authenticate to Google Container Registry using [the official docker-credential-gcr credential helper](https://github.com/GoogleCloudPlatform/docker-credential-gcr).

## Usage

```yml
- name: Configure Docker to Authenticate to GCR
  uses: docker-credential-gcr-action@v2
  with:
    service-account-key: ${{ secrets.GCP_SERVICE_ACCOUNT_KEY }}
```
