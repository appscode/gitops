# Deploy via ArgoCD using Helm charts

<img src="/argocd/helm/argocd-helm-app.png">

- https://argo-cd.readthedocs.io/en/stable/user-guide/helm/

You should install/update the following charts first:

- ace-user-roles
- license-proxyserver

For `license-proxyserver`, you need to configure a token. To get the token, generate an online license-proxyserer from the url:
`https://appscode.com/billing/{{org}}/license-proxy-server` . Then use that token.
