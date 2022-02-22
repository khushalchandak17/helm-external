<a name="unreleased"></a>
## [Unreleased]


<a name="1.0.53"></a>
## [1.0.53] - 2022-02-22
### Feat
- bump snapshot-controller


<a name="1.0.52"></a>
## [1.0.52] - 2022-02-18
### Chore
- revert ingress-nginx to 4.0.8

### Ci
- promote to v1.0.52


<a name="1.0.51"></a>
## [1.0.51] - 2022-02-18
### Chore
- bump ingress-nginx to 4.0.9

### Ci
- promote to v1.0.51


<a name="1.0.50"></a>
## [1.0.50] - 2022-02-08
### Ci
- promote to v1.0.50

### Fix
- velero target customization op-orw-sc-prod01


<a name="1.0.49"></a>
## [1.0.49] - 2022-02-03
### Ci
- promote to v1.0.49

### Fix
- indent


<a name="1.0.48"></a>
## [1.0.48] - 2022-02-03
### Ci
- promote to v1.0.48

### Fix
- set caCert and s3ForcePathStyle


<a name="1.0.47"></a>
## [1.0.47] - 2022-01-31
### Ci
- promote to v1.0.47

### Fix
- set region to default us-east-1 because mandatory but will be ignored


<a name="1.0.46"></a>
## [1.0.46] - 2022-01-31
### Ci
- promote to v1.0.46

### Feat
- add velero vpshere configs

### Fix
- set velero on-prem params


<a name="1.0.44"></a>
## [1.0.44] - 2022-01-31
### Ci
- promote to v1.0.44

### Fix
- reduce cluster-autoscaler scale down delays for wargaming


<a name="1.0.43"></a>
## [1.0.43] - 2022-01-27
### Ci
- promote to v1.0.43

### Fix
- cluster-autoscaler values


<a name="1.0.42"></a>
## [1.0.42] - 2022-01-27
### Ci
- promote to v1.0.42

### Fix
- autoscaler should delete nodes with pods with local storage


<a name="1.0.41"></a>
## [1.0.41] - 2022-01-26
### Ci
- promote to v1.0.41

### Fix
- update cluster-autoscaler targetCustomizations


<a name="1.0.40"></a>
## [1.0.40] - 2022-01-26
### Chore
- bump autoscaler

### Ci
- promote to v1.0.40


<a name="1.0.39"></a>
## [1.0.39] - 2022-01-21
### Ci
- promote to v1.0.39

### Fix
- correct region


<a name="1.0.38"></a>
## [1.0.38] - 2022-01-21
### Ci
- promote to v1.0.38

### Fix
- dont enable CSI on rancher clusters


<a name="1.0.37"></a>
## [1.0.37] - 2022-01-21
### Ci
- promote to v1.0.37

### Feat
- add Velero configs for current AWS clusters


<a name="1.0.36"></a>
## [1.0.36] - 2022-01-21
### Ci
- promote to v1.0.36

### Reverts
- chore: bump ebs-csi to 2.6.2


<a name="1.0.35"></a>
## [1.0.35] - 2022-01-21
### Chore
- bump ebs-csi to 2.6.2

### Ci
- promote to v1.0.35


<a name="1.0.34"></a>
## [1.0.34] - 2022-01-20
### Ci
- promote to v1.0.34

### Fix
- add Velero notice


<a name="1.0.33"></a>
## [1.0.33] - 2022-01-17
### Ci
- promote to v1.0.33

### Feat
- just a basic Velero install with no custom settings


<a name="1.0.32"></a>
## [1.0.32] - 2022-01-13
### Chore
- bump nginx to 4.0.8

### Ci
- promote to v1.0.32


<a name="1.0.31"></a>
## [1.0.31] - 2022-01-13
### Chore
- bump nginx to 4.0.13

### Ci
- promote to v1.0.31


<a name="1.0.30"></a>
## [1.0.30] - 2021-12-10
### Ci
- promote to v1.0.30


<a name="1.0.29"></a>
## [1.0.29] - 2021-12-10
### Ci
- promote to v1.0.29


<a name="1.0.27"></a>
## 1.0.27 - 2021-12-08
### Ci
- promote to v1.0.27


[Unreleased]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.53...HEAD
[1.0.53]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.52...1.0.53
[1.0.52]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.51...1.0.52
[1.0.51]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.50...1.0.51
[1.0.50]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.49...1.0.50
[1.0.49]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.48...1.0.49
[1.0.48]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.47...1.0.48
[1.0.47]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.46...1.0.47
[1.0.46]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.44...1.0.46
[1.0.44]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.43...1.0.44
[1.0.43]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.42...1.0.43
[1.0.42]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.41...1.0.42
[1.0.41]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.40...1.0.41
[1.0.40]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.39...1.0.40
[1.0.39]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.38...1.0.39
[1.0.38]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.37...1.0.38
[1.0.37]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.36...1.0.37
[1.0.36]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.35...1.0.36
[1.0.35]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.34...1.0.35
[1.0.34]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.33...1.0.34
[1.0.33]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.32...1.0.33
[1.0.32]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.31...1.0.32
[1.0.31]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.30...1.0.31
[1.0.30]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.29...1.0.30
[1.0.29]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.27...1.0.29
