# ArgoCD Test

ArgoCD の動作確認用リポジトリ。

## 構成

- `manifests/` - デプロイ対象の Kubernetes マニフェスト
  - namespace.yaml - argocd-test namespace
  - deployment.yaml - nginx Deployment
  - service.yaml - nginx Service
