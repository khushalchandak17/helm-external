# ingress-nginx

**INCOMPATIBLE** with EKS.

Helm [bug](https://github.com/helm/helm/issues/9371)

Example log:

```
time="2021-10-04T15:30:15Z" level=error msg="error syncing 'fleet-shared/ingress-nginx-ingress-nginx': handler bundle: chart requires kubeVersion: >=1.19.0-0 which is incompatible with Kubernetes v1.18.0, requeuing"
```

Upstream [chart](https://github.com/kubernetes/ingress-nginx/blob/main/charts/ingress-nginx) contains this string in [Chart.yaml](https://github.com/kubernetes/ingress-nginx/blob/main/charts/ingress-nginx/Chart.yaml):

```yaml
kubeVersion: ">=1.19.0-0"
```

Example EKS version: `v1.19.13-eks-8df270`

```
Server Version: version.Info{Major:"1", Minor:"19+", GitVersion:"v1.19.13-eks-8df270", GitCommit:"8df2700a72a2598fa3a67c05126fa158fd839620", GitTreeState:"clean", BuildDate:"2021-07-31T01:36:57Z", GoVersion:"go1.15.14", Compiler:"gc", Platform:"linux/amd64"}
```

```bash
kubectl version -o json | jq .serverVersion
```

Output:

```json
{
  "major": "1",
  "minor": "19+",
  "gitVersion": "v1.19.13-eks-8df270",
  "gitCommit": "8df2700a72a2598fa3a67c05126fa158fd839620",
  "gitTreeState": "clean",
  "buildDate": "2021-07-31T01:36:57Z",
  "goVersion": "go1.15.14",
  "compiler": "gc",
  "platform": "linux/amd64"
}
```






