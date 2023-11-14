<a name="unreleased"></a>
## [Unreleased]


<a name="1.0.325"></a>
## [1.0.325] - 2023-11-14
### Chore
- upgrade discontinued istio version and add config for INC0695996


<a name="1.0.324"></a>
## [1.0.324] - 2023-11-09
### Chore
- update efs-csi to v.1.7.0 to provide TCX required fix mount path

### Ci
- promote to v1.0.324


<a name="1.0.323"></a>
## [1.0.323] - 2023-10-17
### Ci
- promote to v1.0.323


<a name="1.0.322"></a>
## [1.0.322] - 2023-10-10
### Ci
- promote to v1.0.322


<a name="1.0.321"></a>
## [1.0.321] - 2023-09-28
### Ci
- promote to v1.0.321

### Nginx
- set "enable-underscores-in-headers" to true


<a name="1.0.320"></a>
## [1.0.320] - 2023-09-26
### Ci
- promote to v1.0.320


<a name="1.0.319"></a>
## [1.0.319] - 2023-09-26
### Ci
- promote to v1.0.319

### Fix
- change the cert manager version


<a name="1.0.318"></a>
## [1.0.318] - 2023-09-26
### Ci
- promote to v1.0.318

### Feat
- set datadog labels using ClusterLabels


<a name="1.0.317"></a>
## [1.0.317] - 2023-09-26
### Ci
- promote to v1.0.317


<a name="1.0.316"></a>
## [1.0.316] - 2023-09-22
### Ci
- promote to v1.0.316


<a name="1.0.315"></a>
## [1.0.315] - 2023-09-18
### Ci
- promote to v1.0.315


<a name="1.0.314"></a>
## [1.0.314] - 2023-09-11
### Ci
- promote to v1.0.314

### Feat
- adding vSphere CPI service & temporary node taint job
- adding vSphere CPI service & temporary node taint job


<a name="1.0.313"></a>
## [1.0.313] - 2023-09-06
### Ci
- promote to v1.0.313


<a name="1.0.312"></a>
## [1.0.312] - 2023-08-28
### Ci
- promote to v1.0.312


<a name="1.0.311"></a>
## [1.0.311] - 2023-08-24
### Chore
- add apac harbor edns config

### Ci
- promote to v1.0.311


<a name="1.0.310"></a>
## [1.0.310] - 2023-08-24
### Ci
- promote to v1.0.310


<a name="1.0.309"></a>
## [1.0.309] - 2023-08-16
### Ci
- promote to v1.0.309


<a name="1.0.308"></a>
## [1.0.308] - 2023-08-15
### Chore
- further simplify edns values since we have all necessary labels on onprem clusters now

### Ci
- promote to v1.0.308

### Feat
- add special case for onprem rancher to manage continental zone records for redirects


<a name="1.0.307"></a>
## [1.0.307] - 2023-08-15
### Ci
- promote to v1.0.307

### Feat
- ingress controller to publish node internal IPs instead of hostnames


<a name="1.0.306"></a>
## [1.0.306] - 2023-08-15
### Ci
- promote to v1.0.306


<a name="1.0.305"></a>
## [1.0.305] - 2023-08-10
### Ci
- promote to v1.0.305


<a name="1.0.304"></a>
## [1.0.304] - 2023-08-09
### Ci
- promote to v1.0.304

### Feat
- use sprig template for autoscaler

### Fix
- fix cluster selector


<a name="1.0.303"></a>
## [1.0.303] - 2023-08-09
### Chore
- use sprig template for onprem clusters

### Ci
- promote to v1.0.303

### Fix
- attempt to fix error "Failed to parse helm values template: template: values:8: bad character U+002D '-'"
- use new cluster-name label instead


<a name="1.0.302"></a>
## [1.0.302] - 2023-08-08
### Chore
- add op-orw-sc-qa03 cluster config

### Ci
- promote to v1.0.302

### Feat
- add apac domains for edns


<a name="1.0.301"></a>
## [1.0.301] - 2023-08-08
### Ci
- promote to v1.0.301

### Fix
- typo in op-orw-sc-qa02 velero config


<a name="1.0.300"></a>
## [1.0.300] - 2023-08-07
### Ci
- promote to v1.0.300

### Fix
- re-add missing files in velero


<a name="1.0.299"></a>
## [1.0.299] - 2023-08-07
### Ci
- promote to v1.0.299

### Feat
- use templated values for velero


<a name="1.0.298"></a>
## 1.0.298 - 2023-08-03
### Ci
- promote to v1.0.298


[Unreleased]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.325...HEAD
[1.0.325]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.324...1.0.325
[1.0.324]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.323...1.0.324
[1.0.323]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.322...1.0.323
[1.0.322]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.321...1.0.322
[1.0.321]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.320...1.0.321
[1.0.320]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.319...1.0.320
[1.0.319]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.318...1.0.319
[1.0.318]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.317...1.0.318
[1.0.317]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.316...1.0.317
[1.0.316]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.315...1.0.316
[1.0.315]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.314...1.0.315
[1.0.314]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.313...1.0.314
[1.0.313]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.312...1.0.313
[1.0.312]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.311...1.0.312
[1.0.311]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.310...1.0.311
[1.0.310]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.309...1.0.310
[1.0.309]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.308...1.0.309
[1.0.308]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.307...1.0.308
[1.0.307]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.306...1.0.307
[1.0.306]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.305...1.0.306
[1.0.305]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.304...1.0.305
[1.0.304]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.303...1.0.304
[1.0.303]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.302...1.0.303
[1.0.302]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.301...1.0.302
[1.0.301]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.300...1.0.301
[1.0.300]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.299...1.0.300
[1.0.299]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.298...1.0.299
