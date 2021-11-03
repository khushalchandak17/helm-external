# aws-efs-csi-driver

Enable it in a `helm-fleetcd*` repository by adding this example snipper in a values file:

```yaml
    - name: efs-csi-driver
      description: EFS CSI Driver
      spec:
        repo: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external.git
        revision: 1.0.13
        paths:
          - aws-efs-csi-driver
        clientSecretName: gitlab
        targets:
          - clusterGroup: aws
```
