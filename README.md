# argocd-lab

Argo CD GitOps 示例仓库，配合笔记使用。

- `guestbook/` — 纯 YAML 清单（directory 方式发布）
- `helm-guestbook/` — Helm Chart 方式发布
- `kustomize-guestbook/` — Kustomize 方式发布
- `apps/` — App of Apps 模式的 Application 定义（含 `root-app.yaml`，root-app 自我管理）

示例应用镜像使用 [podinfo](https://github.com/stefanprodan/podinfo)（多架构，amd64/arm64 均可运行）。
