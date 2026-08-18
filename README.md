# DSMP 服务器规则手册

[![Netlify Status](https://api.netlify.com/api/v1/badges/你的构建状态/deploy-status)](https://dsmpsever.netlify.app/)

**DSMP 服务器** 的官方规则与指南网站，为玩家提供清晰、可搜索的服务器文档。

🔗 **在线访问**：[https://dsmpsever.netlify.app/](https://dsmpsever.netlify.app/)

---

## 📖 包含内容

- **关于本服** — 服务器定位与愿景
- **完整规则体系** — 游玩、建筑、养殖、交流、封禁五章
- **建设方案** — 重大事务的民主决策流程
- **常用指令指南** — 传送、领地、经济等指令速查
- **腐竹与支持** — 关于管理员与反馈渠道

---

## 🛠️ 技术栈

| 工具 | 用途 |
| :--- | :--- |
| [MkDocs](https://www.mkdocs.org/) | 静态文档生成器 |
| [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) | 现代化文档主题 |
| [Netlify](https://www.netlify.com/) | 持续部署与托管 |
| [GitHub](https://github.com/) | 版本控制与协作 |

---

## 🚀 本地运行

```bash
# 克隆仓库
git clone https://github.com/dishuishulu/mc-rules-website.git
cd mc-rules-website

# 安装依赖
pip install -r requirements.txt

# 启动本地预览
mkdocs serve
