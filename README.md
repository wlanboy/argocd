# argocd
argocd deployments

## add kind cluster to argocd
```
argocd cluster add kind-kind
```

## add projects to cluster
```
argocd app create test --repo https://github.com/wlanboy/argocd.git --path test --dest-name kind-kind --dest-namespace test
```
