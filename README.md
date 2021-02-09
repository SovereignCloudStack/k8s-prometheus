# Deployment manifests for Prometheus®

## Attributions

Prometheus is a trademark of The Linux Foundation which is not affiliated with the SCS project.

## Repository content

This repository is intended to include all relevant configuration
and Kubernetes manifests for the deployment of Prometheus inside SCS.

## Repository layout

This repository contains kustomize bases which may be referenced by
kustomize overlays which in turn define the deployment of whole
environments/clusters.

## Automated smoke tests

In order to ensure that every component inside of SCS behaves as
expected, there should be simple smoke tests.
These tests are implemented using GitHub Actions/Workflows.

## References

| | |
| --- | --- |
| CI smoke test | ![Smoke test](https://github.com/SovereignCloudStack/k8s-prometheus/workflows/CI/badge.svg) |
| Upstream website | [prometheus.io](https://prometheus.io/) |
| Upstream repository | [prometheus/prometheus](https://github.com/prometheus/prometheus) |



