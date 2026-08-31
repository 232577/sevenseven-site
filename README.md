# Sevenseven Site (`sevenseven.qzz.io`)

Sevenseven 的公开个人数字工作台，采用新野兽派（Neo-Brutalism）与极简高科技设计语言，纯静态零依赖构建，由 GitHub Pages 自动化全球发布。

---

## 🌟 核心功能与亮点

- ⚡ **零依赖毫秒级渲染**：纯 HTML5 / CSS3 / Vanilla JS 架构，加载时间小于 100ms。
- 🌓 **双模态无缝切换**：
  - **浅色模式**：经典海报蓝 `#173fee`、高对比墨黑边框与网格纸纹理。
  - **深色模式**：高科技暗夜底 `#090d18`、霓虹电光蓝 `#3b66ff` 与高对比文本。
  - 自动跟随系统并由 `localStorage` 本地记忆。
- 🗂️ **多维项目分类看板**：
  - 包含 `全部`、`边缘与在线服务`、`开源仓库`、`实验与工具` 四大筛选分类。
  - 卡片集成状态药丸（🟢 运行中 / 🟡 迭代中 / 🔵 规划中）、技术栈 Tag 与一键复制地址。
- 📡 **服务健康监测 Pulse**：直观展示 Worker 边缘计算、静态托管与 HTTPS 链路健康度。
- ✦ **发展里程碑与演进时间轴**：清晰记录版本迭代与近期规划。
- 📋 **快捷交互工具箱**：一键复制管理员邮箱、一键复制 GitHub 地址、回到顶部平滑滚动。
- 🚀 **SEO & PWA 全面就绪**：
  - 完整的 OpenGraph / Twitter Cards 社交分享卡片元数据。
  - JSON-LD 结构化数据（`schema.org/WebSite`）。
  - `manifest.json`、`robots.txt`、`sitemap.xml` 完备支持。

---

## 💻 本地预览与调试

在项目目录中运行任意静态 HTTP 服务即可：

```powershell
npx --yes serve .
```

或使用 Python 内置服务器：

```powershell
python -m http.server 8080
```

打开浏览器访问 `http://localhost:8080` 即可预览。

---

## 🚢 部署与发布

本仓库已配置自定义域名：`sevenseven.qzz.io`（通过 `CNAME` 文件生效）。

1. 将代码提交并推送到 GitHub `main` 分支：
   ```bash
   git add .
   git commit -m "feat: 升级 Sevenseven 工作台 2.0"
   git push origin main
   ```
2. GitHub Pages 会自动拉取根目录最新文件并完成发布。

---

## 📁 目录结构

```
sevenseven-site/
├── .github/workflows/ci.yml # CI 质量校验流水线
├── 404.html                 # 404 错误缺省页
├── CNAME                    # GitHub Pages 自定义域名绑定 (sevenseven.qzz.io)
├── favicon.svg              # 高清矢量品牌图标
├── index.html               # 核心首页与交互逻辑
├── manifest.json            # PWA 应用配置
├── robots.txt               # 搜索引擎抓取规则
├── sitemap.xml              # 站点地图
└── README.md                # 项目文档
```

---

## ✉️ 联系与反馈

- **作者**：Sevenseven
- **GitHub**：[https://github.com/232577](https://github.com/232577)
- **邮箱**：[2325778716@qq.com](mailto:2325778716@qq.com)
