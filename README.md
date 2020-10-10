# stubernetes-core

This is a Kustomization that installs the core components for Stubernetes:

- The Weave Net CNI
- The Flux GitOps Toolkit
- Resources to deploy [the rest of the system](https://github.com/stuartpb/stubernetes-system)

## Moved

Active development on this repository has moved to [the main stubernetes repository](https://github.com/stuartpb/stubernetes/tree/main/core).

## Installing

`kubectl apply -k https://github.com/stuartpb/stubernetes-core`
