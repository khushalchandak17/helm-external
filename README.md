# Helm External

[Fleet](https://fleet.rancher.io) configuration files for upstream Helm charts.

## Upstream sources

| Description                                    | Directory                                                  | Source                                                                                                     |
|:-----------------------------------------------|:-----------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------|
| AWS EBS CSI Driver                             | [aws-ebs-csi-driver](aws-ebs-csi-driver)                   | [Repository](https://github.com/kubernetes-sigs/aws-ebs-csi-driver/tree/master/charts/aws-ebs-csi-driver)  |
| AWS EFS CSI Driver                             | [aws-efs-csi-driver](aws-efs-csi-driver)                   | [Repository](https://github.com/kubernetes-sigs/aws-efs-csi-driver/tree/master/charts/aws-efs-csi-driver)  |
| Cert Manager                                   | [cert-manager](cert-manager)                               | [Repository](https://github.com/jetstack/cert-manager/tree/master/deploy/charts/cert-manager)              |
| Cluster Autoscaler                             | [cluster-autoscaler](cluster-autoscaler)                   | [Repository](https://github.com/kubernetes/autoscaler/tree/master/charts/cluster-autoscaler)               |
| NginX Ingress Controller                       | [ingress-nginx](ingress-nginx)                             | [Repository](https://github.com/kubernetes/ingress-nginx/tree/main/charts/ingress-nginx)                   |
| Metrics Server                                 | [metrics-server](metrics-server)                           | [Repository](https://github.com/bitnami/charts/tree/master/bitnami/metrics-server)                         |
| OPA Gatekeeper                                 | [rancher-gatekeeper](rancher-gatekeeper)                   | [Repository](https://github.com/rancher/charts/tree/dev-v2.6/charts/rancher-gatekeeper)                    |
| OPA Gatekeeper (`crd`)                         | [rancher-gatekeeper-crd](rancher-gatekeeper-crd)           | [Repository](https://github.com/rancher/charts/tree/dev-v2.6/charts/rancher-gatekeeper-crd)                |
| CSI snapshot controller                        | [snapshot-controller](snapshot-controller)                 | [Repository](https://github.com/piraeusdatastore/helm-charts/tree/main/charts/snapshot-controller)         |
| CSI snapshot controller (`validation webhook`) | [snapshot-validation-webhook](snapshot-validation-webhook) | [Repository](https://github.com/piraeusdatastore/helm-charts/tree/main/charts/snapshot-validation-webhook) |
| Velero backup                                  | [velero](velero)                                           | [Repository](https://github.com/vmware-tanzu/helm-charts/tree/main/charts/velero)                          |
