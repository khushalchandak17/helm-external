# trident-operator

Installs NetApp's [Trident](https://github.com/NetApp/trident) CSI Storage Orchestrator.

* Helm [chart](https://github.com/NetApp/trident/tree/master/helm/trident-operator)
* Storage Backend configuration handled by custom [chart](https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-tridentbackend)
* Required Secrets sealed with [helm-secrets]() chart
  * `tbe-mentor` for Mentor's storage appliance credentials
  * `dockerhub` for Docker Hub image registry credentials

## GitRepo

Add the following in a Fleet Workspace [repository](https://gitlab.industrysoftware.automation.siemens.com/caas-ops/fleet):

```yaml
- name: trident-backend
  create: true
  description: NetApp Trident CSI Backend
  spec:
    repo: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-tridentbackend.git
    revision: 1.0.40
    clientSecretName: gitlab-caas-ops
    targets:
      - name: all
        clusterSelector: {}

- name: trident-operator
  create: true
  description: NetApp Trident CSI
  spec:
    repo: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external.git
    revision: 1.0.288
    paths:
      - trident-operator
    clientSecretName: gitlab-caas-ops
    targets:
      - name: all
        clusterSelector: {}
```

## Issues

* This Rancher [issue](https://github.com/rancher/rancher/issues/41191). Rancher's webhook prevents the operator from patching its namespace.
  - Patched with Kustomize but it's not ideal
  - Once issue is resolved, either by Rancher or by trident Helm chart allows us capability to add `management.cattle.io/projects/updatepsa` permission for Pod Security Admission (such as issue [trident/#840](https://github.com/NetApp/trident/pull/840)), then this Kustomization should be removed.
