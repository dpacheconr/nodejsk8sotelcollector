# nodejsk8sotelcollector
```
helm repo add open-telemetry https://open-telemetry.github.io/opentelemetry-helm-charts
helm repo update
helm upgrade --install otel-collector open-telemetry/opentelemetry-collector --set config.exporters.otlp.headers.api-key="YOUR_INGEST_LICENSE_KEY" -f values.yaml
```