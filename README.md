# forecastle

Self-hosted serverless CI + CD workloads on K8s.

## overview

There are two primary components within forecastle. The first is the **workload manager**. This
allows for incoming hooks to trigger new builds, API calls to be made, and to serve the needs of
the UI. The workload manager is the brain of forecastle, and represents the source of truth.
The second major component is the **workloads** themselves. These are the containers that
represent your code + tests (e.g. unit tests, integration tests, deployment steps, etc).

## usage

### workload manager

_TBD: configure + deploy to GKE_

### workloads

_TBD: configure K/V file and push container_

