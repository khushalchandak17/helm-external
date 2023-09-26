<a name="unreleased"></a>
## [Unreleased]


<a name="1.0.317"></a>
## [1.0.317] - 2023-09-26

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
## [1.0.298] - 2023-08-03
### Ci
- promote to v1.0.298


<a name="1.0.297"></a>
## [1.0.297] - 2023-08-03
### Ci
- promote to v1.0.297


<a name="1.0.296"></a>
## [1.0.296] - 2023-08-01
### Ci
- promote to v1.0.296

### Fix
- rancher workload can't be dependent on local harbor


<a name="1.0.295"></a>
## [1.0.295] - 2023-07-28
### Chore
- add velero config for apac svcs cluster

### Ci
- promote to v1.0.295


<a name="1.0.294"></a>
## [1.0.294] - 2023-07-28
### Chore
- cloudability for rancher apac

### Ci
- promote to v1.0.294


<a name="1.0.293"></a>
## [1.0.293] - 2023-07-28
### Ci
- promote to v1.0.293

### Fix
- rancher apac


<a name="1.0.292"></a>
## [1.0.292] - 2023-07-28
### Ci
- promote to v1.0.292

### Fix
- rancher apac config


<a name="1.0.291"></a>
## [1.0.291] - 2023-07-28
### Chore
- add config for rancher apac

### Ci
- promote to v1.0.291


<a name="1.0.290"></a>
## 1.0.290 - 2023-07-28
### Ci
- promote to v1.0.290


[Unreleased]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.317...HEAD
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
[1.0.298]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.297...1.0.298
[1.0.297]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.296...1.0.297
[1.0.296]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.295...1.0.296
[1.0.295]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.294...1.0.295
[1.0.294]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.293...1.0.294
[1.0.293]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.292...1.0.293
[1.0.292]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.291...1.0.292
[1.0.291]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.290...1.0.291
