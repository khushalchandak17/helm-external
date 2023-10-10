# Helm External

[Fleet](https://fleet.rancher.io) configuration files for upstream Helm charts.

## Upstream sources

| Description                                    | Directory :arrow_down:                                                      | Source                                                                                                     |
| :--------------------------------------------- | :-------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| AWS EBS CSI Driver                             | [aws-ebs-csi-driver](aws-ebs-csi-driver)                                    | [Repository](https://github.com/kubernetes-sigs/aws-ebs-csi-driver/tree/master/charts/aws-ebs-csi-driver)  |
| AWS EFS CSI Driver                             | [aws-efs-csi-driver](aws-efs-csi-driver)                                    | [Repository](https://github.com/kubernetes-sigs/aws-efs-csi-driver/tree/master/charts/aws-efs-csi-driver)  |
| Cert Manager                                   | [cert-manager](cert-manager)                                                | [Repository](https://github.com/jetstack/cert-manager/tree/master/deploy/charts/cert-manager)              |
| Cloudability (metrics agent)                   | [cloudability](cloudability)                                                | [Repository](https://cloudability.github.io/metrics-agent/)                                                |
| Cluster Autoscaler                             | [cluster-autoscaler](cluster-autoscaler)                                    | [Repository](https://github.com/kubernetes/autoscaler/tree/master/charts/cluster-autoscaler)               |
| Datadog (agent)                                | [datadog](datadog)                                                          | [Repository](https://github.com/DataDog/helm-charts/tree/main/charts/datadog)                              |
| External DNS                                   | [external-dns](external-dns)                                                | [Repository](https://github.com/kubernetes-sigs/external-dns/tree/master/charts/external-dns)              |
| NginX Ingress Controller                       | [ingress-nginx](ingress-nginx)                                              | [Repository](https://github.com/kubernetes/ingress-nginx/tree/main/charts/ingress-nginx)                   |
| Istio                                          | [istio](istio)                                                              | [Repository](https://github.com/istio/istio/tree/master/manifests/charts)                                  |
| Metrics Server                                 | [metrics-server](metrics-server)                                            | [Repository](https://github.com/bitnami/charts/tree/master/bitnami/metrics-server)                         |
| OPA Gatekeeper                                 | [rancher-gatekeeper](rancher-gatekeeper)                                    | [Repository](https://github.com/rancher/charts/tree/dev-v2.6/charts/rancher-gatekeeper)                    |
| OPA Gatekeeper (`crd`)                         | [rancher-gatekeeper-crd](rancher-gatekeeper-crd)                            | [Repository](https://github.com/rancher/charts/tree/dev-v2.6/charts/rancher-gatekeeper-crd)                |
| [DEPRECATED] Rancher Istio                     | [rancher-istio](rancher-istio)                                              | [Repository](https://github.com/rancher/charts/tree/dev-v2.6/charts/rancher-istio)                         |
| Reloader                                       | [reloader-global](reloader-global) & [reloader-singlens](reloader-singlens) | [Repository](https://github.com/stakater/Reloader/tree/master/deployments/kubernetes/chart/reloader)       |
| Sealed Secrets                                 | [sealed-secrets](sealed-secrets)                                            | [Repository](https://github.com/bitnami-labs/sealed-secrets/tree/main/helm/sealed-secrets)                 |
| CSI snapshot controller                        | [snapshot-controller](snapshot-controller)                                  | [Repository](https://github.com/piraeusdatastore/helm-charts/tree/main/charts/snapshot-controller)         |
| CSI snapshot controller (`validation webhook`) | [snapshot-validation-webhook](snapshot-validation-webhook)                  | [Repository](https://github.com/piraeusdatastore/helm-charts/tree/main/charts/snapshot-validation-webhook) |
| Telepresence                                   | [telepresence](telepresence)                                                | [Repository](https://github.com/telepresenceio/telepresence/tree/release/v2/charts/telepresence)           |
| Trident Operator                               | [trident-operator](trident-operator)                                        | [Repository](https://github.com/NetApp/trident/tree/master/helm/trident-operator)                          |
| Velero backup                                  | [velero](velero)                                                            | [Repository](https://github.com/vmware-tanzu/helm-charts/tree/main/charts/velero)                          |
