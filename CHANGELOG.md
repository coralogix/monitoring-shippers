# Changelog

## Coralogix Opentelemetry Integration

### v0.12.1 / 2023-09-29

* [FIX] Remove `k8s.pod.name`,`k8s.job.name` and `k8s.node.name` from subsystem attribute list
* [FIX] Add tolerations

### v0.12.0 / 2023-08-22
* [FIX] Change `k8s.container.name` to `k8s.pod.name` attribute

### v0.11.0 / 2023-08-22
* [FEATURE] Support host.id from system resource detector.

### v0.10.0 / 2023-08-11
* [FEATURE] Align the `cx.otel_integration.name` attribute with new internal requirements

### v0.9.0 / 2023-08-08
* [FIX] Limit kube-state-metrics scraping to chart's instance only
* [FIX] Move extra Kubernetes metrics to collector instead of agent
* [FEATURE] Make `k8s.node.name` label the target node for Kubernetes node info metric

### v0.8.0 / 2023-08-03
* [FEATURE] Add cluster metrics related to allocatable resources (CPU, memory)

### v0.7.0 / 2023-08-02
* [FIX] Re-add metrics filtering
* [CHORE] Remove unused `cx.otel_integration.version` attribute

### v0.6.0 / 2023-08-01
* [FEATURE] Add `container_fs_usage_bytes` metric
* [FEATURE] Add `k8s.node.name` resource attribute
* [FEATURE] Override detection for cloud provider detectors
* [CHORE] Update OpenTelemetry charts to 0.64.0

### v0.5.0 / 2023-07-26
* [FEATURE] Add cluster metrics receiver

### v0.4.0 / 2023-07-17
* [FEATURE] Add additional k8s metrics to filter

### v0.3.0 / 2023-07-12
* [FEATURE] Adding extra kubelet and kubernetes API metrics
* [FEATURE] Adding region detection
* [CHORE] Update OpenTelemetry charts to 0.62.2

### v0.2.0 / 2023-06-19
* [FEATURE] Adding cluster name

### v0.1.0 / 2023-06-19
* [FEATURE] Initial version
