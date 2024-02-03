# flux2-kustomize-helm-example

1. Playground example to discover flux in a simulated use-case.
2. Forked from the official flux2 example repo.
3. Base, staging and production environments exist but only staging is used.

## Usage

1. Bootstrap the cluster with "flux bootstrap" with required parameters.
2. This is pretty much it, watch flux deploy infra-controllers --> infra-configs --> apps in given order.
