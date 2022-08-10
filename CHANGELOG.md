<a name="unreleased"></a>
## [Unreleased]


<a name="1.0.140"></a>
## [1.0.140] - 2022-08-10
### Fix
- disable nginx run on hostNetwork to allow calico iptables to work


<a name="1.0.139"></a>
## [1.0.139] - 2022-08-09
### Ci
- promote to v1.0.139

### Fix
- bump velero, allow upgrade of CRDs


<a name="1.0.138"></a>
## [1.0.138] - 2022-08-02
### Ci
- promote to v1.0.138

### Fix
- remove duplcate key


<a name="1.0.137"></a>
## [1.0.137] - 2022-08-02
### Ci
- promote to v1.0.137

### Feat
- upgrades


<a name="1.0.136"></a>
## [1.0.136] - 2022-08-02
### Ci
- promote to v1.0.136
- promote only on main branch, yq eval does not validate well


<a name="1.0.134"></a>
## [1.0.134] - 2022-08-02

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
## 1.0.108 - 2022-06-15
### Ci
- promote to v1.0.108


[Unreleased]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.140...HEAD
[1.0.140]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.139...1.0.140
[1.0.139]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.138...1.0.139
[1.0.138]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.137...1.0.138
[1.0.137]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.136...1.0.137
[1.0.136]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.134...1.0.136
[1.0.134]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.132...1.0.134
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
