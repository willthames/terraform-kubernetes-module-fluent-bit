helm repo add fluent https://fluent.github.io/helm-charts
helm repo update
helm template fluent-bit fluent/fluent-bit --namespace monitoring --output-dir base --values values.yaml

