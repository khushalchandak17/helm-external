<a name="unreleased"></a>
## [Unreleased]


<a name="1.0.136"></a>
## [1.0.136] - 2022-08-02
### Ci
- promote only on main branch, yq eval does not validate well


<a name="1.0.134"></a>
## [1.0.134] - 2022-08-02

<a name="1.0.133"></a>
## [1.0.133] - 2022-08-01
### Chore
- upgrade
- bump velero version (1.9.0)
- bump cluster-autoscaler
- move common value

### Ci
- promote to v1.0.133
- promote to v1.0.79
- promote to v1.0.78
- promote to v1.0.77
- promote to v1.0.76
- promote to v1.0.75
- promote to v1.0.74
- promote to v1.0.73
- promote to v1.0.72

### Feat
- initial reloader install
- set replicas and resources
- upgrades
- Velero add aws-euce1-sc-qa01 customization

### Fix
- merge conflict
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
- version bump
- formatting
- ranchereu-prod velero bucket prefix
- rename aws-euce1-rc-svcs01 velero conf
- ranchereuprod-control-eu-central-1 naming
- Velero - add euce1 target customizations

### Test
- assumerole
- fast key rotation


<a name="1.0.132"></a>
## [1.0.132] - 2022-07-28
### Ci
- promote to v1.0.132

### Fix
- cleanup


<a name="1.0.131"></a>
## [1.0.131] - 2022-07-26
### Ci
- promote to v1.0.131

### Feat
- enable daily snapshots on every cluster


<a name="1.0.130"></a>
## [1.0.130] - 2022-07-15
### Chore
- add velero values for aws-usea1-sc-train01

### Ci
- promote to v1.0.130


<a name="1.0.129"></a>
## [1.0.129] - 2022-07-13
### Ci
- promote to v1.0.129


<a name="1.0.128"></a>
## [1.0.128] - 2022-07-06
### Chore
- bump Velero plugins

### Ci
- promote to v1.0.128


<a name="1.0.127"></a>
## [1.0.127] - 2022-07-06
### Chore
- bump Velero version

### Ci
- promote to v1.0.127


<a name="1.0.125"></a>
## [1.0.125] - 2022-07-04
### Ci
- promote to v1.0.125


<a name="1.0.124"></a>
## [1.0.124] - 2022-07-04
### Ci
- promote to v1.0.124


<a name="1.0.123"></a>
## [1.0.123] - 2022-07-01
### Ci
- promote to v1.0.123

### Feat
- update rancher-gatekeeper and enable Validation Webhook only on select clusters


<a name="1.0.122"></a>
## [1.0.122] - 2022-06-30
### Ci
- promote to v1.0.122


<a name="1.0.121"></a>
## [1.0.121] - 2022-06-29
### Ci
- promote to v1.0.121


<a name="1.0.120"></a>
## [1.0.120] - 2022-06-29
### Ci
- promote to v1.0.120

### Fix
- remove fleet dependency potentially can cause issue


<a name="1.0.119"></a>
## [1.0.119] - 2022-06-29
### Ci
- promote to v1.0.119

### Fix
- dont upgrade Velero CRDs


<a name="1.0.118"></a>
## [1.0.118] - 2022-06-28
### Ci
- promote to v1.0.118


<a name="1.0.117"></a>
## [1.0.117] - 2022-06-28
### Ci
- promote to v1.0.117


<a name="1.0.116"></a>
## [1.0.116] - 2022-06-28
### Ci
- promote to v1.0.116

### Fix
- ns for external-dns release should be edns-system


<a name="1.0.115"></a>
## [1.0.115] - 2022-06-28
### Ci
- promote to v1.0.115

### Feat
- initial external-dns config


<a name="1.0.114"></a>
## [1.0.114] - 2022-06-23
### Ci
- promote to v1.0.114

### Feat
- add BundleDiff for velero deployment


<a name="1.0.113"></a>
## [1.0.113] - 2022-06-23
### Ci
- promote to v1.0.113

### Feat
- add clustermatcher for op-orw-mom-prod04


<a name="1.0.109"></a>
## [1.0.109] - 2022-06-23
### Ci
- promote to v1.0.109

### Feat
- customize for op-orw-mom-prod04


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


<a name="1.0.103"></a>
## [1.0.103] - 2022-06-08
### Ci
- promote to v1.0.103


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


[Unreleased]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.136...HEAD
[1.0.136]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.134...1.0.136
[1.0.134]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.133...1.0.134
[1.0.133]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.132...1.0.133
[1.0.132]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.131...1.0.132
[1.0.131]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.130...1.0.131
[1.0.130]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.129...1.0.130
[1.0.129]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.128...1.0.129
[1.0.128]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.127...1.0.128
[1.0.127]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.125...1.0.127
[1.0.125]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.124...1.0.125
[1.0.124]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.123...1.0.124
[1.0.123]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.122...1.0.123
[1.0.122]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.121...1.0.122
[1.0.121]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.120...1.0.121
[1.0.120]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.119...1.0.120
[1.0.119]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.118...1.0.119
[1.0.118]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.117...1.0.118
[1.0.117]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.116...1.0.117
[1.0.116]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.115...1.0.116
[1.0.115]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.114...1.0.115
[1.0.114]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.113...1.0.114
[1.0.113]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.109...1.0.113
[1.0.109]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.108...1.0.109
[1.0.108]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.107...1.0.108
[1.0.107]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.106...1.0.107
[1.0.106]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.105...1.0.106
[1.0.105]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.104...1.0.105
[1.0.104]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.103...1.0.104
[1.0.103]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.101...1.0.103
[1.0.101]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.100...1.0.101
[1.0.100]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.79...1.0.100
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
[1.0.67]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.26...1.0.67
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
