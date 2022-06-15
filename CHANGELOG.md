<a name="unreleased"></a>
## [Unreleased]


<a name="1.0.108"></a>
## [1.0.108] - 2022-06-15
### Feat
- customize autoscaler and velero for aws-euce1-rc-gblsvcs01eu


<a name="1.0.107"></a>
## [1.0.107] - 2022-06-14
### Ci
- promote to v1.0.107

### Fix
- downgrade aws-efs-csi-driver


<a name="1.0.106"></a>
## [1.0.106] - 2022-06-14
### Ci
- promote to v1.0.106


<a name="1.0.105"></a>
## [1.0.105] - 2022-06-14
### Ci
- promote to v1.0.105

### Fix
- remove example targetCustomization


<a name="1.0.104"></a>
## [1.0.104] - 2022-06-09
### Ci
- promote to v1.0.104

### Fix
- (calico) move installation cr to kustomization


<a name="1.0.103"></a>
## [1.0.103] - 2022-06-08
### Ci
- promote to v1.0.103

### Feat
- add calico aws fleet config


<a name="1.0.101"></a>
## [1.0.101] - 2022-06-08
### Ci
- promote to v1.0.101

### Fix
- eu-central-1 dev cluster name


<a name="1.0.100"></a>
## [1.0.100] - 2022-06-07
### Ci
- promote to v1.0.100

### Feat
- customize for dev01-dev


<a name="1.0.99"></a>
## [1.0.99] - 2022-06-07
### Ci
- promote to v1.0.99

### Feat
- bump ingress-nginx version and enable admissionWebhooks


<a name="1.0.98"></a>
## [1.0.98] - 2022-06-07
### Ci
- promote to v1.0.98

### Fix
- metrics-server format


<a name="1.0.97"></a>
## [1.0.97] - 2022-06-06
### Chore
- bump aws-ebs-csi-driver

### Ci
- promote to v1.0.97


<a name="1.0.96"></a>
## [1.0.96] - 2022-06-06
### Chore
- bump metrics-server

### Ci
- promote to v1.0.96

### Fix
- add safe.directory to GitlabCI


<a name="1.0.95"></a>
## [1.0.95] - 2022-05-26
### Ci
- promote to v1.0.95

### Feat
- enable snapshots on AWS prod clusters
- add EFS driver dockerhub secret


<a name="1.0.94"></a>
## [1.0.94] - 2022-05-26
### Ci
- promote to v1.0.94

### Feat
- add daily snapshots


<a name="1.0.93"></a>
## [1.0.93] - 2022-05-25
### Ci
- promote to v1.0.93

### Fix
- move imagePullSecrets, add more pullPolicy


<a name="1.0.92"></a>
## [1.0.92] - 2022-05-25
### Ci
- promote to v1.0.92

### Fix
- add dockerhub imagePullSecret


<a name="1.0.91"></a>
## [1.0.91] - 2022-05-25
### Chore
- bump upstream version and improve values

### Ci
- promote to v1.0.91

### Feat
- bymp upstream version and customize for aws-usea1-tcx-preprod02


<a name="1.0.90"></a>
## [1.0.90] - 2022-05-25
### Ci
- promote to v1.0.90

### Feat
- add aws-usea1-tcx-preprod02 customization


<a name="1.0.89"></a>
## [1.0.89] - 2022-05-20
### Ci
- promote to v1.0.89

### Velero
- test existingSecret in op-orw-kaas-qa03


<a name="1.0.88"></a>
## [1.0.88] - 2022-05-19
### Ci
- promote to v1.0.88

### Velero
- add config to targetCustomizations


<a name="1.0.87"></a>
## [1.0.87] - 2022-05-19
### Ci
- promote to v1.0.87

### Velero
- config for op-orw-kaas-qa03


<a name="1.0.86"></a>
## [1.0.86] - 2022-05-19
### Ci
- promote to v1.0.86

### Feat
- add pullSecrets to sealed-secrets


<a name="1.0.85"></a>
## [1.0.85] - 2022-05-19
### Chore
- update list of upstream charts

### Ci
- promote to v1.0.85


<a name="1.0.84"></a>
## 1.0.84 - 2022-05-18
### Ci
- promote to v1.0.84

### Sealedsecrets
- set keyrenewperiod in hours


[Unreleased]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.108...HEAD
[1.0.108]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.107...1.0.108
[1.0.107]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.106...1.0.107
[1.0.106]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.105...1.0.106
[1.0.105]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.104...1.0.105
[1.0.104]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.103...1.0.104
[1.0.103]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.101...1.0.103
[1.0.101]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.100...1.0.101
[1.0.100]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.99...1.0.100
[1.0.99]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.98...1.0.99
[1.0.98]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.97...1.0.98
[1.0.97]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.96...1.0.97
[1.0.96]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.95...1.0.96
[1.0.95]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.94...1.0.95
[1.0.94]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.93...1.0.94
[1.0.93]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.92...1.0.93
[1.0.92]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.91...1.0.92
[1.0.91]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.90...1.0.91
[1.0.90]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.89...1.0.90
[1.0.89]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.88...1.0.89
[1.0.88]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.87...1.0.88
[1.0.87]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.86...1.0.87
[1.0.86]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.85...1.0.86
[1.0.85]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.84...1.0.85
