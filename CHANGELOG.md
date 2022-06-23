<a name="unreleased"></a>
## [Unreleased]


<a name="1.0.113"></a>
## [1.0.113] - 2022-06-23
### Feat
- add clustermatcher for op-orw-mom-prod04


<a name="1.0.109"></a>
## [1.0.109] - 2022-06-23
### Ci
- promote to v1.0.109

### Feat
- customize for op-orw-mom-prod04


<a name="1.0.112"></a>
## [1.0.112] - 2022-06-22
### Chore
- bump cluster-autoscaler
- move common value

### Ci
- promote to v1.0.112
- promote to v1.0.79
- promote to v1.0.78
- promote to v1.0.77
- promote to v1.0.76
- promote to v1.0.75
- promote to v1.0.74
- promote to v1.0.73
- promote to v1.0.72
- promote to v1.0.71
- promote to v1.0.70
- promote to v1.0.69
- promote to v1.0.68
- promote to v1.0.67
- promote to v1.0.66
- promote to v1.0.65
- promote to v1.0.64
- promote to v1.0.70
- promote to v1.0.69
- promote to v1.0.68
- promote to v1.0.67
- promote to v1.0.66
- promote to v1.0.65
- promote to v1.0.64
- promote to v1.0.63

### Feat
- upgrades
- customise for aws-usea1-sc-qa01
- Velero add aws-euce1-sc-qa01 customization

### Fix
- make external-dns use "route53" sealedsecret by default
- dns-manager -> route53
- move values to dedicated file
- set policy=sync, restore txtprefix
- try suffix
- remove prefix
- set logging to debug level
- filter namespace,domain,source
- set iam-user creds by reference
- new attempt
- update assume-role
- set assumerole as SA annotation
- txtPrefix
- set fullnameOverride
- make txtPrefix dynamic
- set prefix and increase interval
- version bump
- formatting
- ranchereu-prod velero bucket prefix
- rename aws-euce1-rc-svcs01 velero conf
- ranchereuprod-control-eu-central-1 naming
- Velero - add euce1 target customizations
- disable gatekeeper validating webhook for AWS us-east-1 QA clusters
- gatekeeper validating webhook per cluster override
- move ns exempt to siemens-opa chart
- disable gatekeeper validating webhook for AWS us-east-1 QA clusters
- gatekeeper validating webhook per cluster override
- move ns exempt to siemens-opa chart

### Test
- assumerole
- fast key rotation
- OPA on eu-west-1 wargame03
- opa on wargame03
- OPA on eu-west-1 wargame03
- opa on wargame03


<a name="1.0.108"></a>
## [1.0.108] - 2022-06-15
### Ci
- promote to v1.0.108

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


<a name="1.0.79"></a>
## [1.0.79] - 2022-04-21
### Ci
- promote to v1.0.79

### Fix
- version bump


<a name="1.0.78"></a>
## [1.0.78] - 2022-04-20
### Ci
- promote to v1.0.78

### Fix
- formatting


<a name="1.0.77"></a>
## [1.0.77] - 2022-04-20
### Ci
- promote to v1.0.77

### Fix
- ranchereu-prod velero bucket prefix


<a name="1.0.76"></a>
## [1.0.76] - 2022-04-20
### Ci
- promote to v1.0.76

### Feat
- Velero add aws-euce1-sc-qa01 customization


<a name="1.0.75"></a>
## [1.0.75] - 2022-04-20
### Ci
- promote to v1.0.75

### Fix
- rename aws-euce1-rc-svcs01 velero conf


<a name="1.0.74"></a>
## [1.0.74] - 2022-04-20
### Ci
- promote to v1.0.74

### Fix
- ranchereuprod-control-eu-central-1 naming


<a name="1.0.73"></a>
## [1.0.73] - 2022-04-20
### Chore
- move common value

### Ci
- promote to v1.0.73


<a name="1.0.72"></a>
## [1.0.72] - 2022-04-20
### Ci
- promote to v1.0.72

### Fix
- Velero - add euce1 target customizations


<a name="1.0.71"></a>
## [1.0.71] - 2022-04-20
### Ci
- promote to v1.0.71
- promote to v1.0.70
- promote to v1.0.69
- promote to v1.0.68
- promote to v1.0.67
- promote to v1.0.66
- promote to v1.0.65
- promote to v1.0.64

### Fix
- disable gatekeeper validating webhook for AWS us-east-1 QA clusters
- gatekeeper validating webhook per cluster override
- move ns exempt to siemens-opa chart

### Test
- OPA on eu-west-1 wargame03
- opa on wargame03


<a name="1.0.70"></a>
## [1.0.70] - 2022-03-23
### Ci
- promote to v1.0.70


<a name="1.0.69"></a>
## [1.0.69] - 2022-03-15
### Ci
- promote to v1.0.69

### Test
- OPA on eu-west-1 wargame03


<a name="1.0.68"></a>
## [1.0.68] - 2022-03-15
### Ci
- promote to v1.0.68

### Test
- opa on wargame03


<a name="1.0.67"></a>
## [1.0.67] - 2022-03-04
### Ci
- promote to v1.0.67

### Fix
- disable gatekeeper validating webhook for AWS us-east-1 QA clusters


<a name="1.0.66"></a>
## [1.0.66] - 2022-03-04
### Ci
- promote to v1.0.66

### Fix
- gatekeeper validating webhook per cluster override


<a name="1.0.65"></a>
## [1.0.65] - 2022-03-03
### Ci
- promote to v1.0.65

### Fix
- move ns exempt to siemens-opa chart


<a name="1.0.64"></a>
## [1.0.64] - 2022-03-03
### Ci
- promote to v1.0.64


<a name="1.0.63"></a>
## [1.0.63] - 2022-03-03
### Ci
- promote to v1.0.63


<a name="1.0.62"></a>
## [1.0.62] - 2022-03-03
### Ci
- promote to v1.0.62


<a name="1.0.61"></a>
## [1.0.61] - 2022-03-03
### Ci
- promote to v1.0.61


<a name="1.0.26"></a>
## [1.0.26] - 2021-12-06
### Ci
- promote to v1.0.26

### Fix
- correct naming convention


<a name="1.0.25"></a>
## [1.0.25] - 2021-12-03
### Ci
- promote to v1.0.25

### Fix
- version bump


<a name="1.0.24"></a>
## [1.0.24] - 2021-12-03
### Ci
- promote to v1.0.24

### Feat
- add qa clusters to hpa customizations


<a name="1.0.23"></a>
## [1.0.23] - 2021-11-22
### Ci
- promote to v1.0.23

### Fix
- customise autoscaler for aws-usea1-rc-svcs01


<a name="1.0.22"></a>
## [1.0.22] - 2021-11-22
### Ci
- promote to v1.0.22

### Fix
- override clustername for all current prod clusters


<a name="1.0.21"></a>
## [1.0.21] - 2021-11-19
### Ci
- promote to v1.0.21

### Fix
- override clustername


<a name="1.0.20"></a>
## [1.0.20] - 2021-11-11
### Ci
- promote to v1.0.20

### Fix
- bump ingress-nginx


<a name="1.0.19"></a>
## [1.0.19] - 2021-11-11
### Ci
- promote to v1.0.19

### Fix
- patch ingress-nginx


<a name="1.0.18"></a>
## [1.0.18] - 2021-11-11
### Ci
- promote to v1.0.18

### Fix
- empty targetCustomizations


<a name="1.0.17"></a>
## [1.0.17] - 2021-11-10
### Ci
- promote to v1.0.17

### Fix
- update README


<a name="1.0.16"></a>
## [1.0.16] - 2021-11-09
### Ci
- promote to v1.0.16

### Feat
- add ingress-nginx


<a name="1.0.15"></a>
## [1.0.15] - 2021-11-09
### Ci
- promote to v1.0.15


<a name="1.0.14"></a>
## [1.0.14] - 2021-11-05
### Ci
- promote to v1.0.14

### Feat
- add EFS readme


<a name="1.0.13"></a>
## [1.0.13] - 2021-11-02
### Ci
- promote to v1.0.13

### Fix
- bump upstream chart to 2.2.0
- bump upstream chart to 2.4.0


<a name="1.0.12"></a>
## [1.0.12] - 2021-10-26
### Ci
- promote to v1.0.12

### Fix
- cleanup _issue, use branch instead


<a name="1.0.11"></a>
## [1.0.11] - 2021-10-26
### Ci
- promote to v1.0.11

### Fix
- use apache for troubleshooting


<a name="1.0.10"></a>
## [1.0.10] - 2021-10-11
### Ci
- promote to v1.0.10

### Feat
- bump cert-manager


<a name="1.0.9"></a>
## [1.0.9] - 2021-10-07
### Ci
- promote to v1.0.9

### Fix
- set release names and improve formatting


<a name="1.0.8"></a>
## [1.0.8] - 2021-10-06
### Ci
- promote to v1.0.8

### Feat
- remove ebs and ebs SCs config


<a name="1.0.7"></a>
## [1.0.7] - 2021-10-06
### Ci
- promote to v1.0.7

### Fix
- remove upstream ingress-nginx


<a name="1.0.6"></a>
## [1.0.6] - 2021-10-05
### Ci
- promote to v1.0.6

### Fix
- rename dirs


<a name="1.0.5"></a>
## [1.0.5] - 2021-10-04
### Ci
- promote to v1.0.5

### Fix
- ingress-nginx is incompatible


<a name="1.0.4"></a>
## [1.0.4] - 2021-10-04
### Ci
- promote to v1.0.4

### Fix
- use defaultNamespace instead of namespace


<a name="1.0.3"></a>
## [1.0.3] - 2021-10-04
### Ci
- promote to v1.0.3
- enable debug


<a name="1.0.2"></a>
## [1.0.2] - 2021-10-04
### Ci
- promote to v1.0.2
- validate YAML

### Feat
- add OPA


<a name="1.0.1"></a>
## [1.0.1] - 2021-10-01
### Fix
- cert-manager - use defaultNamespace


<a name="1.0.0"></a>
## 1.0.0 - 2021-09-07
### Feat
- add fleet files for external charts


[Unreleased]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.113...HEAD
[1.0.113]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.109...1.0.113
[1.0.109]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.112...1.0.109
[1.0.112]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.108...1.0.112
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
[1.0.86]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.79...1.0.86
[1.0.79]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.78...1.0.79
[1.0.78]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.77...1.0.78
[1.0.77]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.76...1.0.77
[1.0.76]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.75...1.0.76
[1.0.75]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.74...1.0.75
[1.0.74]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.73...1.0.74
[1.0.73]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.72...1.0.73
[1.0.72]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.71...1.0.72
[1.0.71]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.70...1.0.71
[1.0.70]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.69...1.0.70
[1.0.69]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.68...1.0.69
[1.0.68]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.67...1.0.68
[1.0.67]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.66...1.0.67
[1.0.66]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.65...1.0.66
[1.0.65]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.64...1.0.65
[1.0.64]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.63...1.0.64
[1.0.63]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.62...1.0.63
[1.0.62]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.61...1.0.62
[1.0.61]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.26...1.0.61
[1.0.26]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.25...1.0.26
[1.0.25]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.24...1.0.25
[1.0.24]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.23...1.0.24
[1.0.23]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.22...1.0.23
[1.0.22]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.21...1.0.22
[1.0.21]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.20...1.0.21
[1.0.20]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.19...1.0.20
[1.0.19]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.18...1.0.19
[1.0.18]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.17...1.0.18
[1.0.17]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.16...1.0.17
[1.0.16]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.15...1.0.16
[1.0.15]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.14...1.0.15
[1.0.14]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.13...1.0.14
[1.0.13]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.12...1.0.13
[1.0.12]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.11...1.0.12
[1.0.11]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.10...1.0.11
[1.0.10]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.9...1.0.10
[1.0.9]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.8...1.0.9
[1.0.8]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.7...1.0.8
[1.0.7]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.6...1.0.7
[1.0.6]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.5...1.0.6
[1.0.5]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.4...1.0.5
[1.0.4]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.3...1.0.4
[1.0.3]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.2...1.0.3
[1.0.2]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.1...1.0.2
[1.0.1]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.0...1.0.1
