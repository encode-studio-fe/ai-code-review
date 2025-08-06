# Encode Code Review

印客学院--基于本地和github代码进行code review

## License

[MIT](./LICENSE) License © [Encode Studio](https://github.com/encode-studio-fe)

## 特性

- 🤖 **自动代码审查**: 对合并请求和提交进行自动化审查，提供差异分析
- 🧠 **智能反馈**: 通过AI模型提供代码质量评估、最佳实践建议和性能优化建议
- ⚙️ **灵活配置**: 支持多种AI模型和自定义审查规则，管理配置优先级
- 🔄 **持续集成**: 与CI/CD工具集成，实现自动触发和结果通知

### 主要模块

- **CLI入口**: 处理命令行输入和执行相应操作
- **配置管理**: 处理多来源配置的加载和合并
- **平台服务**: 提供与不同代码托管平台的集成
- **AI提供者**: 封装不同AI服务的调用逻辑
- **代码审查核心**: 处理代码差异分析和审查逻辑

## 安装

```bash
# 全局安装
npm install -g encode-code-review

# 或使用pnpm
pnpm add -g encode-code-review

# 或使用yarn
yarn global add encode-code-review
```