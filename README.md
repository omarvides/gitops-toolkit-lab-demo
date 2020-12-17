# Gitops Toolkit lab demo

## Bootstraping gitops toolkit

```shell
flux bootstrap github \
  --components=source-controller,kustomize-controller,notification-controller \
  --owner=omarvides \
  --repository=el-toolkit-lab-demo \
  --path=clusters/production \
  --personal
```
