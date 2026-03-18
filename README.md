# Home Assistant Add-on: Arcadia

这是一个给 Home Assistant OS / Supervisor 使用的 Arcadia 自定义 Add-on 包装仓库目录。

## 说明

这个目录不是 Arcadia 源码本体，而是一个 Home Assistant Add-on 封装。

它直接使用上游镜像：

`supermanito/arcadia`

并将 Home Assistant Add-on 的持久化目录映射到容器内的：

`/arcadia`

从而兼容 Arcadia 所需的目录结构。
