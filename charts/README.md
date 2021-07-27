# How to run

```
# DRY-RUN
helm upgrade otel-tracing opentelemetry-collector --install --atomic --debug --dry-run --namespace zz-workorder-hub --version 0.5.9 --timeout 60s -f values.yaml

# RUN
helm upgrade otel-tracing opentelemetry-collector --install --atomic --debug --namespace zz-workorder-hub --version 0.5.9 --timeout 60s -f values.yaml
```