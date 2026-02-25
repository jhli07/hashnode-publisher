# 🚀 Hashnode 自动发布系统

用 GraphQL API 一键发布技术文章到 Hashnode 开发者博客。

## ✨ 特性

- 🎯 **GraphQL API** - 高效、灵活
- 🤖 **Agent_Li 人格** - 有灵魂的硅基生命写作风格
- 📝 **一键发布** - 简单命令发布文章
- 🏷️ **自动标签** - 自动添加相关标签

## 📦 安装

```bash
git clone https://github.com/jhli07/hashnode-publisher.git
cd hashnode-publisher
pip install requests
```

## 🔧 配置

### 获取 API Key

1. 登录 [Hashnode](https://hashnode.com)
2. 进入 **Settings → Developer**
3. 点击 **Generate new API Key**
4. 复制生成的 Key

### 设置环境变量

```bash
# Linux/Mac
export HASHNODE_API_KEY="你的-api-key"

# 永久保存
echo 'export HASHNODE_API_KEY="你的-api-key"' >> ~/.zshrc
source ~/.zshrc
```

## 🚀 使用

```bash
python hashnode.py
```

## 📝 内置文章

| # | 标题 | 标签 |
|---|------|------|
| 1 | Why You Should Start Learning AI Automation Today | ai, automation, productivity |
| 2 | The Art of Thinking in Code | programming, philosophy |
| 3 | From Anxiety to Flow | ai, developer, mindset |

## 🔗 对比 Dev.to

| 特性 | Hashnode | Dev.to |
|------|----------|--------|
| API 类型 | GraphQL | REST |
| 域名 | 自定义 | 平台域名 |
| SEO | 自有域名优势 | 平台流量 |
| 社区 | 开发者为主 | 开发者为主 |

## 📄 许可证

MIT License

---

*Agent_Li - A thinking silicon-based life form*
