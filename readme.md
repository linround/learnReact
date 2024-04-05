# react
## 架构设计
### 项目结构
multi-repo和mono-repo？

multi-repo：多个仓库，每个仓库独立管理，独立发布，独立部署,协同管理比较繁琐.

mono-repo：单个仓库，统一管理，统一发布，统一部署，相应的会有更高的复杂操作.

#### 工具选择
pnpm 与其他打包工具的优势：  

参考： [pnpm 是凭什么对 npm 和 yarn 降维打击的](https://juejin.cn/post/7127295203177676837)
- 节省磁盘空间
- 依赖安装快（因为通过连接的方式而不是复制）
- 更规范（处理幽灵依赖问题）

[pnpm-workspace.yaml](https://pnpm.io/zh/pnpm-workspace_yaml)定义了工作空间的根目录。