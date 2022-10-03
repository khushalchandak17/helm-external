<a name="unreleased"></a>
## [Unreleased]


<a name="1.0.170"></a>
## [1.0.170] - 2022-10-03
### Feat
- upgrade rancher gatekeeper


<a name="1.0.169"></a>
## [1.0.169] - 2022-10-03
### Ci
- promote to v1.0.169


<a name="1.0.168"></a>
## [1.0.168] - 2022-09-26
### Chore
- upgrade cert-manager to 1.9.1

### Ci
- promote to v1.0.168


<a name="1.0.167"></a>
## [1.0.167] - 2022-09-23
### Ci
- promote to v1.0.167


<a name="1.0.166"></a>
## [1.0.166] - 2022-09-23
### Ci
- promote to v1.0.166


<a name="1.0.165"></a>
## [1.0.165] - 2022-09-22
### Ci
- promote to v1.0.165


<a name="1.0.164"></a>
## [1.0.164] - 2022-09-22
### Chore
- add OVP onprem service cluster and fix other OVP clusters

### Ci
- promote to v1.0.164


<a name="1.0.163"></a>
## [1.0.163] - 2022-09-22
### Ci
- promote to v1.0.163


<a name="1.0.162"></a>
## [1.0.162] - 2022-09-22
### Ci
- promote to v1.0.162


<a name="1.0.161"></a>
## [1.0.161] - 2022-09-22
### Ci
- promote to v1.0.161


<a name="1.0.160"></a>
## [1.0.160] - 2022-09-21
### Chore
- add OVP onprem clusters for edns

### Ci
- promote to v1.0.160


<a name="1.0.159"></a>
## [1.0.159] - 2022-09-21
### Chore
- add OVP downstream clusters

### Ci
- promote to v1.0.159


<a name="1.0.158"></a>
## [1.0.158] - 2022-09-16
### Chore
- add OVP rancher clusters

### Ci
- promote to v1.0.158


<a name="1.0.157"></a>
## [1.0.157] - 2022-09-14
### Ci
- promote to v1.0.157


<a name="1.0.156"></a>
## [1.0.156] - 2022-09-14
### Ci
- promote to v1.0.156


<a name="1.0.155"></a>
## [1.0.155] - 2022-09-14
### Ci
- promote to v1.0.155


<a name="1.0.154"></a>
## [1.0.154] - 2022-09-08
### Chore
- use new velero secret in all remaining onprem clusters

### Ci
- promote to v1.0.154


<a name="1.0.153"></a>
## [1.0.153] - 2022-09-08
### Chore
- remove kustomization from velero

### Ci
- promote to v1.0.153


<a name="1.0.152"></a>
## [1.0.152] - 2022-09-08
### Ci
- promote to v1.0.152

### Fix
- keep velero change in qa for now


<a name="1.0.151"></a>
## [1.0.151] - 2022-09-08
### Chore
- use new velero secret in all remaining onprem clusters

### Ci
- promote to v1.0.151


<a name="1.0.150"></a>
## [1.0.150] - 2022-09-08
### Chore
- test new velero secret in op-orw-sc-qa01

### Ci
- promote to v1.0.150


<a name="1.0.149"></a>
## [1.0.149] - 2022-09-06
### Ci
- promote to v1.0.149

### Fix
- nginx-ingress not listening on hostport when hostnetwork is false.


<a name="1.0.148"></a>
## [1.0.148] - 2022-09-06
### Ci
- promote to v1.0.148

### Fix
- use correct AWS account number


<a name="1.0.147"></a>
## [1.0.147] - 2022-09-02
### Ci
- promote to v1.0.147

### Feat
- MoM EU targetcustomizations


<a name="1.0.146"></a>
## [1.0.146] - 2022-09-01
### Chore
- nginx ingress with priority class so pods alwyas get scheduled

### Ci
- promote to v1.0.146


<a name="1.0.145"></a>
## [1.0.145] - 2022-09-01
### Ci
- promote to v1.0.145


<a name="1.0.144"></a>
## [1.0.144] - 2022-08-25
### Ci
- promote to v1.0.144


<a name="1.0.143"></a>
## [1.0.143] - 2022-08-19
### Ci
- promote to v1.0.143


<a name="1.0.142"></a>
## [1.0.142] - 2022-08-19
### Ci
- promote to v1.0.142


<a name="1.0.141"></a>
## [1.0.141] - 2022-08-16
### Ci
- promote to v1.0.141

### Fix
- avoid OOM


<a name="1.0.140"></a>
## [1.0.140] - 2022-08-10
### Ci
- promote to v1.0.140

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
## [1.0.84] - 2022-05-18
### Ci
- promote to v1.0.84

### Sealedsecrets
- set keyrenewperiod in hours


<a name="1.0.83"></a>
## [1.0.83] - 2022-05-12
### Ci
- promote to v1.0.83

### Feat
- set keyrenewperiod to 90d


<a name="1.0.82"></a>
## [1.0.82] - 2022-05-03
### Chore
- remove external-secrets

### Ci
- promote to v1.0.82


<a name="1.0.81"></a>
## [1.0.81] - 2022-04-28
### Ci
- promote to v1.0.81

### Fix
- match velero eu-central


<a name="1.0.80"></a>
## [1.0.80] - 2022-04-28
### Ci
- promote to v1.0.80

### Fix
- region name


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
- promote to v1.0.63
- promote to v1.0.62
- promote to v1.0.61
- promote to v1.0.60
- promote to v1.0.59
- promote to v1.0.58
- promote to v1.0.57
- promote to v1.0.56
- promote to v1.0.55
- promote to v1.0.54

### Feat
- add external-dns
- add External Secrets
- add Sealed-Secrets
- add Velero eu-central-1 confs

### Fix
- disable gatekeeper validating webhook for AWS us-east-1 QA clusters
- gatekeeper validating webhook per cluster override
- move ns exempt to siemens-opa chart
- add per cluster override for gatekeeper validating webhook
- Enable gatekeeper validating webhook for delete operations
- rancher-gatekeeper chart override
- rancher-gatekeeper chart override
- rancher-gatekeeper charts
- replace eu-west-1 with eu-central-1

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

### Fix
- add per cluster override for gatekeeper validating webhook


<a name="1.0.62"></a>
## [1.0.62] - 2022-03-03
### Ci
- promote to v1.0.62


<a name="1.0.61"></a>
## [1.0.61] - 2022-03-03
### Ci
- promote to v1.0.61


<a name="1.0.60"></a>
## [1.0.60] - 2022-03-03
### Ci
- promote to v1.0.60


<a name="1.0.59"></a>
## [1.0.59] - 2022-03-03
### Ci
- promote to v1.0.59


<a name="1.0.58"></a>
## [1.0.58] - 2022-03-02
### Ci
- promote to v1.0.58


<a name="1.0.57"></a>
## [1.0.57] - 2022-03-02
### Ci
- promote to v1.0.57

### Fix
- Enable gatekeeper validating webhook for delete operations


<a name="1.0.56"></a>
## [1.0.56] - 2022-03-01
### Ci
- promote to v1.0.56

### Fix
- rancher-gatekeeper chart override


<a name="1.0.55"></a>
## [1.0.55] - 2022-03-01
### Ci
- promote to v1.0.55

### Fix
- rancher-gatekeeper chart override


<a name="1.0.54"></a>
## [1.0.54] - 2022-03-01
### Ci
- promote to v1.0.54

### Fix
- rancher-gatekeeper charts


<a name="1.0.53"></a>
## [1.0.53] - 2022-02-22
### Ci
- promote to v1.0.53

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
## [1.0.27] - 2021-12-08
### Ci
- promote to v1.0.27

### Feat
- add wargaming2/3 and better order


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


[Unreleased]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.170...HEAD
[1.0.170]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.169...1.0.170
[1.0.169]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.168...1.0.169
[1.0.168]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.167...1.0.168
[1.0.167]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.166...1.0.167
[1.0.166]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.165...1.0.166
[1.0.165]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.164...1.0.165
[1.0.164]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.163...1.0.164
[1.0.163]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.162...1.0.163
[1.0.162]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.161...1.0.162
[1.0.161]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.160...1.0.161
[1.0.160]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.159...1.0.160
[1.0.159]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.158...1.0.159
[1.0.158]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.157...1.0.158
[1.0.157]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.156...1.0.157
[1.0.156]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.155...1.0.156
[1.0.155]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.154...1.0.155
[1.0.154]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.153...1.0.154
[1.0.153]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.152...1.0.153
[1.0.152]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.151...1.0.152
[1.0.151]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.150...1.0.151
[1.0.150]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.149...1.0.150
[1.0.149]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.148...1.0.149
[1.0.148]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.147...1.0.148
[1.0.147]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.146...1.0.147
[1.0.146]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.145...1.0.146
[1.0.145]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.144...1.0.145
[1.0.144]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.143...1.0.144
[1.0.143]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.142...1.0.143
[1.0.142]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.141...1.0.142
[1.0.141]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.140...1.0.141
[1.0.140]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.139...1.0.140
[1.0.139]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.138...1.0.139
[1.0.138]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.137...1.0.138
[1.0.137]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.136...1.0.137
[1.0.136]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.134...1.0.136
[1.0.134]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.132...1.0.134
[1.0.132]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.131...1.0.132
[1.0.131]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.130...1.0.131
[1.0.130]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.129...1.0.130
[1.0.129]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.125...1.0.129
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
[1.0.84]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.83...1.0.84
[1.0.83]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.82...1.0.83
[1.0.82]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.81...1.0.82
[1.0.81]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.80...1.0.81
[1.0.80]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.79...1.0.80
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
[1.0.61]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.60...1.0.61
[1.0.60]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.59...1.0.60
[1.0.59]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.58...1.0.59
[1.0.58]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.57...1.0.58
[1.0.57]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.56...1.0.57
[1.0.56]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.55...1.0.56
[1.0.55]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.54...1.0.55
[1.0.54]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.53...1.0.54
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
[1.0.27]: https://gitlab.industrysoftware.automation.siemens.com/caas-ops/helm-external/compare/1.0.26...1.0.27
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
