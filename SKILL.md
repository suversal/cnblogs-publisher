# CNBlogs Publisher Skill

通过 MetaWeblog API 管理博客园（CNBlogs）文章的 OpenClaw Skill

## 快速开始

```bash
# 1. 配置环境变量
export CNBLOGS_TOKEN="your-metaweblog-token"

# 2. 保存草稿
python scripts/save_draft.py "标题" "content.md" "分类1,分类2"

# 3. 发布文章
python scripts/publish.py <post-id>
```

## 功能

- ✅ 保存草稿
- 📋 获取文章列表
- 📄 获取单篇文章
- ✏️ 更新草稿
- 🚀 发布文章
- 🗑️ 删除文章

## 详细文档

参见 [README.md](README.md)

## 配置

在博客园设置 → 其他设置中获取 MetaWeblog 访问令牌。

## 测试

```bash
./tests/test_all.sh
```

## 许可证

MIT
