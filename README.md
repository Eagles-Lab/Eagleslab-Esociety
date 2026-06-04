# Eagles Lab 社区

<p align="center">
  <img src="https://img.shields.io/badge/Firebase-10.12-FFCA28?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
  <img src="https://img.shields.io/badge/TailwindCSS-3.4-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white" alt="TailwindCSS">
  <img src="https://img.shields.io/github/license/Eagles-Lab/Eagleslab-Esociety?style=flat-square" alt="License">
</p>

<p align="center">
  <strong>Eagles Lab 技术社区</strong><br>
  专注网安、运维、面试、大厂等技术方向的交流平台
</p>

<p align="center">
  <a href="https://eagleslab.github.io/club/">🌐 在线访问</a> •
  <a href="https://github.com/Eagles-Lab/Eagleslab-Esociety">📦 GitHub</a>
</p>

---

## ✨ 功能特性

### 📝 帖子系统
- ✅ 发帖支持 **Markdown 语法**
- ✅ 帖子**编辑**功能（显示修改时间）
- ✅ 帖子**删除**功能（级联删除评论）
- ✅ 帖子**分享**（独立链接）
- ✅ **置顶帖子**和**标记精华**

### 💬 评论系统
- ✅ **盖楼模式**（类似百度贴吧）
- ✅ **追评**（回复评论）
- ✅ 评论支持 **Markdown** 语法
- ✅ 评论**置顶**功能
- ✅ 评论**删除**功能

### ❤️ 互动功能
- ✅ **点赞系统**（事务保护，防并发）
- ✅ 防抖锁（防止重复点击）

### 👤 用户系统
- ✅ **GitHub OAuth** 登录
- ✅ 用户名修改
- ✅ 角色权限管理

### 🏷️ 板块分类
- ✅ **网安** - 网络安全技术
- ✅ **运维** - 运维开发技术
- ✅ **面经** - 面试经验分享
- ✅ **大厂** - 大厂资讯讨论
- ✅ **形势** - 行业形势分析
- ✅ **其他** - 综合讨论

### 💬 实时聊天室
- ✅ 实时消息推送
- ✅ 管理员可**开启/关闭**
- ✅ 需要**邀请码**或**管理员授权**
- ✅ **屏蔽词**机制

### 🌤️ 其他功能
- ✅ **实时天气**显示
- ✅ 搜索过滤
- ✅ 多维度排序
- ✅ 响应式设计
- ✅ 深色模式

---

## 🚀 快速开始

### 1. Fork 或克隆仓库

```bash
git clone https://github.com/Eagles-Lab/Eagleslab-Esociety.git
cd Eagleslab-Esociety
```

### 2. 配置 Firebase

项目使用 Firebase 作为后端服务。编辑 `assets/js/firebase-config.js`，填入你的 Firebase 配置。

### 3. 配置 GitHub OAuth

1. 访问 https://github.com/settings/developers
2. 创建 OAuth App
3. 在 Firebase Authentication 中启用 GitHub

### 4. 部署到 GitHub Pages

推送到 GitHub 后，在仓库 Settings → Pages 中启用。

---

## 📁 项目结构

```
Eagleslab-Esociety/
├── index.html                  # 主页面
├── assets/
│   ├── js/
│   │   └── firebase-config.js  # Firebase 配置
│   └── vendor/                 # 第三方库
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions
├── LICENSE
└── README.md
```

---

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| **HTML5** | 页面结构 |
| **Tailwind CSS** | 样式框架 |
| **JavaScript** | 业务逻辑 |
| **Firebase Auth** | 用户认证 |
| **Firebase Firestore** | 数据库 |
| **Marked.js** | Markdown 渲染 |
| **Highlight.js** | 代码高亮 |
| **Lucide Icons** | 图标库 |
| **wttr.in** | 天气 API |

---

## 📄 许可证

[MIT](LICENSE)

---

## 🙏 致谢

- [wttr.in](https://wttr.in) - 免费天气 API
- [Tailwind CSS](https://tailwindcss.com) - CSS 框架
- [Lucide Icons](https://lucide.dev) - 图标库
- [Firebase](https://firebase.google.com) - 后端服务

---

## 📞 联系我们

- **GitHub**: https://github.com/Eagles-Lab/Eagleslab-Esociety

---

<p align="center">
  <strong>Eagles Lab 技术社区</strong><br>
  <em>网安 · 运维 · 面经 · 大厂 · 形势</em>
</p>
