# clone-image

# 使用方式

1. 在目录中提交构建文件, 例如

```
FROM gcr.io/kubernetes-helm/tiller:v2.13.1
```

2. 在 hub.docker.com 平台中配置构建

构建为每个 gcr.io 创建独立仓库

每个项目的构建命名方式为, 账户名/仓库名:项目.原tag 如：

holewall/gcr.io:tiller.v2.13.1



