# 个人简历页 · Resume

用纯 **HTML + CSS** 手写的一份响应式个人简历网页，不依赖任何框架和构建工具，双击就能在浏览器里打开。

## 预览

### 👉 [在线预览](https://macoto-wcr.github.io/resume/)

也可以在本地直接打开 `index.html`：

```
code/resume/index.html
```

## 页面结构

| 区块 | 内容 |
| --- | --- |
| 顶部导航 | 吸顶导航栏，点击跳转到对应章节 |
| 简介 | 一句话自我介绍 |
| 技能 | 三列卡片网格，展示 HTML / CSS / JS / Git 等 |
| 经历 | 时间线式学习经历卡片 |
| 联系 | 姓名、电话、留言表单 |
| 回到顶部 | 右下角悬浮按钮 |

## 用到的技术

- **语义化 HTML**：`nav` / `header` / `main` / `section` / `footer`
- **Flexbox**：导航栏、经历卡片排布
- **Grid**：技能区三列布局，窄屏自动变一列
- **响应式**：`@media (max-width: 768px)` 适配手机
- **交互细节**：`scroll-behavior: smooth` 平滑滚动、`position: sticky` 吸顶、`:hover` / `:focus` 过渡效果

## 文件说明

```
resume/
├── index.html   # 全部内容：结构 + 样式都在同一个文件里
└── README.md
```

## 后续计划

- [ ] 接入 JavaScript，让「发送」按钮真的能处理表单
- [x] 开启 GitHub Pages 上线
- [ ] 持续更新简历内容

## 关于我

大三在读，正在从零系统学习前端开发。

---

© 2026 吴诚睿 · 用 HTML + CSS 手写
