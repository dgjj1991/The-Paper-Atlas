# The Paper Atlas (The Chengdu Paper) — 项目记忆与维护指南

## 1. 项目基本信息
- **本地项目路径**: `/Users/junjiehuang/Documents/Ai专用/The Chengdu Paper`
- **GitHub 远程仓库**: `https://github.com/dgjj1991/The-Paper-Atlas.git`
- **GitHub Pages 线上地址**: `https://dgjj1991.github.io/The-Paper-Atlas/`
- **建站系统工作流**: 跳过 Publii 客户端渲染，直接由 AI 处理标准 HTML/CSS 排版，本地预览确认后通过 `git push origin main` 一键部署到 GitHub Pages。

---

## 2. 核心架构与页面索引

### 🏠 总门户 (Portal Hub)
- `index.html`: 保持纯粹的网站理念介绍 + 🇨🇳 中文专区与 🌍 English Edition 两个入口介绍。

### 🇨🇳 中文专栏 (Chinese Edition)
- `cn/index.html`: 深度白皮书列表页。
- **包含的核心专题**:
  - **【🎓 成都教育专题：人文学养、儿童友好与独立思考】**: 涵盖童年秘密档案馆、成都有杏书店、老鱼的机巧屋、空舟美术馆。
- **已收录白皮书文件**:
  1. `cn/youxing-bookstore.html` — 成都有杏书店
  2. `cn/jinqin-teahouse.html` — 成都金琴老茶馆
  3. `cn/jahbar.html` — 家吧 JahBar
  4. `cn/maan-coffee.html` — 漫咖啡（锦江店）
  5. `cn/tongnian-mimiguan.html` — 童年秘密档案馆
  6. `cn/kongzhou-art-museum.html` — 空舟美术馆
  7. `cn/laoyu-automata.html` — 老鱼的机巧屋

### 🌍 英文专栏 (English Edition)
- `en/index.html`: Discover China / The Chengdu Paper 英文列表页。
- **已收录英文指南文件**:
  1. `en/youxing-bookstore.html`
  2. `en/jinqin-teahouse.html`
  3. `en/jahbar.html`
  4. `en/maan-coffee.html`
  5. `en/tongnian-mimiguan.html`
  6. `en/kongzhou-art-museum.html`
  7. `en/laoyu-automata.html`

---

## 3. 标准维护规范 (Workflow Standard)

1. **更新原则**:
   - 优先在本地修改 HTML/CSS，生成双语白皮书。
   - 提供本地预览链接：`file:///Users/junjiehuang/Documents/Ai专用/The Chengdu Paper/index.html`。
   - **除非用户明确要求“推送到 GitHub / 上线”，否则不擅自执行 git push**。
2. **推送命令**:
   - `git add . && git commit -m "..." && git push origin main`
