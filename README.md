[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-908a85?logo=gitpod)](https://gitpod.io/#https://github.com/nodes-app/action-docker-credential-gcr)

# action-docker-credential-gcr

Action for configuring Docker to authenticate to Google Container Registry using [the official docker-credential-gcr credential helper](https://github.com/GoogleCloudPlatform/docker-credential-gcr).

## Usage

```yml
- name: Configure Docker to Authenticate to GCR
  uses: nodes-app/action-docker-credential-gcr@v2
  with:
    service-account-key: ${{ secrets.GCP_SERVICE_ACCOUNT_KEY }}
```
