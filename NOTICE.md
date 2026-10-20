代码采用 MIT（见 LICENSE）。assets/ 中角色宣传图与 pluginIcon.svg 内嵌角色美术单独授权，不适用 MIT；迁移保留原作者及授权说明。素材授权未证实时不得新增公开分发。


## 独立仓库开发与发布

见 [MIGRATION.md](MIGRATION.md)。测试需要真实 CLI，不允许因缺少 Go 跳过 LSP 测试。VS Code 测试 CLI 来自 core-source.json 固定 SHA 的独立临时克隆，构建失败即测试失败。核心仓库的目标地址依赖 Transfer 完成；现有 Marketplace 版本与用户设置保持不变。
