# niflhum.github.io

> 个人博客 · 托管于 GitHub Pages · 域名 [niflhum.top](https://niflhum.top)

## 📋 简介

这是我的个人博客，记录技术学习与生活随笔。

- **主题**：Freemind.386（DOS 复古风格）
- **引擎**：Hexo（Markdown → 静态 HTML）
- **域名**：niflhum.top（阿里云 DNS → GitHub Pages）

## 🗂️ 仓库结构

```
niflhum.github.io/
├── 2017/           # 2017 年文章（前端学习、英语笔记）
├── 2026/           # 2026 年文章（Hexo 重建后）
├── archives/       # 归档页
├── categories/     # 分类页
├── tags/           # 标签页
├── css/            # Bootstrap + 自定义样式
├── js/             # jQuery + Bootstrap + 交互脚本
├── fonts/          # Fixedsys500c 字体（复古终端风）
├── img/            # 图片资源
├── fancybox/       # 图片灯箱
├── index.html      # 首页
└── CNAME           # 自定义域名绑定
```

## 🔗 关联项目

- [gwsw](https://github.com/niflhum/gwsw) - 公文办理单录入系统（侧边栏有链接）

## 🛠️ 本地开发

源文件在独立目录 `~/niflhum-blog/`：

```bash
# 新建文章
cd ~/niflhum-blog
hexo new "文章标题"

# 本地预览
hexo server

# 发布
./deploy.sh
```

## 📜 历史

- **2017**：创建博客，使用 Hexo + Freemind.386 主题
- **2026**：重建 Hexo 源文件结构，保留原有主题风格

---

© 2017-2026 niflhum
