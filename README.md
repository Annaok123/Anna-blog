# 周娜娜 — 对外个人品牌官网

> 🌐 **在线访问：** https://annaok123.github.io/Anna-blog/

## 项目简介

周娜娜的个人品牌官网，展示高级项目经理的专业能力、项目经历与工作方法论。

## 技术栈
本项目使用QClaw工具生成

- **前端：** 纯 HTML + CSS + JavaScript（零框架依赖）
- **字体：** Google Fonts（Fraunces + Plus Jakarta Sans + JetBrains Mono）
- **托管：** GitHub Pages（从 `/docs` 目录自动部署）

## 网站结构

```
docs/
  index.html   ← 网站全部内容（单文件实现）
```

## 设计特点

- 深色高端品牌风格（暗夜底色 + 靛蓝渐变）
- 全屏 Hero + 动态渐变背景 + 浮动几何图形
- 滚动触发动画 + 数字计数器动画
- 响应式设计（桌面 / 平板 / 手机）
- 全站零图片依赖，纯 CSS 渲染

## 内容模块

| 模块 | 内容 |
|------|------|
| Hero | 能力主张 + 实时数据面板 |
| About | 职业叙事 + 核心亮点卡片 |
| Experience | 四段工作经历时间线 |
| Projects | 6个代表项目 + 量化成果 |
| Capabilities | 6项核心能力 + 认证徽章 |
| Philosophy | 四条工作方法论金句 |
| Contact | 联系信息 + 留言表单 |

## 本地预览

```bash
# 克隆仓库后，进入 docs 目录直接打开
open docs/index.html

# 或启动本地服务器
cd docs && python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

## 更新网站

网站直接从 `docs/index.html` 渲染，推送到 `main` 分支后 GitHub Pages 自动构建部署（约1-2分钟）。

## 联系

- 📧 zhounanaok@163.com
- 📱 185-5977-3382
- 📍 深圳
