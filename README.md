# The terrible, horrible, no good, very bad, terrible Homelab Kubernetes Cluster - Keycloak service

This repository is a separated configuration from the [giant(?) monorepo](https://github.com/ahinh43/homelab-k8s-config) that contains the rest of the helm configs for Keycloak. The separation was needed because ArgoCD kept triggering updates and rolling restarts per every commit made in the monorepo regardless of path.

### License

The repo is available under the MIT License.


See [LICENSE.md](LICENSE.md) for the full information