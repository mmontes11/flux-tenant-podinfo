# flux-tenant-podinfo

Tenant repository bootstrapped by [flux-infrastructure](https://github.com/mmontes11/flux-infrastructure) that contains the resources and infrastructure for the [podinfo](https://github.com/mmontes11/podinfo) application.

### Clusters

This tenant can be bootstrapped in multiple clusters just by adding `Kustomization` resources on the [clusters](./clusters) folder.

### Infrastructure

Tenant specific infrastructure required for the apps to run:
- [redis](./infrastructure/redis) 

### Apps

Appplication resources that will be bootstrapped after the infrastructure is reconciled:
- [podinfo](./apps/podinfo)