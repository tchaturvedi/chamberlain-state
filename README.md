# chamberlain-state

GitOps state repo for `chamberlain`. ArgoCD's source of truth: the desired cluster state that
`chamberlain`'s API and controllers reconcile against and commit to.

See [chamberlain](https://github.com/tchaturvedi/chamberlain) for the control plane itself, and
[tchaturvedi.github.io](https://tchaturvedi.github.io/) for the project write-up.

## Status

`namespace.yaml` is a placeholder so `chamberlain`'s `just up` has something real to sync via
ArgoCD from zero. Real tenant/workload state replaces it starting Stage 1.
