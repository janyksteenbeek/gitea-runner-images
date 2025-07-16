# gitea-runner-images mirror

This repo contains a weekly GitHub Action that mirrors the following Gitea Docker images from Docker Hub to GitHub Container Registry (GHCR):

### Mirrored Images

| Source Image | GHCR Target |
| ------------ | ----------- |
| `gitea/runner-images:ubuntu-latest` | `ghcr.io/janyksteenbeek/gitea-runner-images:runner-images-ubuntu-latest` |
| `gitea/act_runner:nightly-dind-rootless` | `ghcr.io/janyksteenbeek/gitea-runner-images:act-runner-nightly-dind-rootless` |

### Schedule

This mirror runs every week, at Monday night at **02:00 UTC**.

### Manual Trigger

You can also run the workflow manually via the "Run workflow" button on GitHub.