# 💬 Chat-Record-Generator

一个轻量级、纯前端的聊天记录结构化生成器，支持自定义角色、实时预览和一键导出 TXT / Markdown。

---

## ✨ 功能亮点

- 🎭 **双角色自定义**  
  左右输入框分别对应不同角色，名称可随时修改并实时生效。
- ⚡ **即时预览**  
  发送后立即在中间区域生成带时间戳的格式化记录。
- 📄 **一键导出**  
  支持 `.txt` 纯文本与 `.md` Markdown 两种格式，文件名自动带时间戳。
- 🔄 **回车快捷发送**  
  `Enter` 直接发送，`Shift+Enter` 换行，操作流畅。
- 📊 **实时统计**  
  显示总消息数、各角色消息占比。
- 🧹 **安全清空**  
  二次确认后清空所有记录，防止误操作。
- 📱 **响应式布局**  
  手机、平板、桌面多端完美适配。
- 🌐 **纯前端实现**  
  无需后端，直接打开 `index.html` 即可使用。

---

## 🚀 快速开始

1. **克隆或下载**
   ```bash
   git clone https://github.com/你的用户名/chat-record-generator.git
   cd chat-record-generator

2. **运行**  
   双击 `index.html` 即可在浏览器打开使用。

---

## 📖 使用示例

| 步骤 | 操作                        | 效果                                                         |
| ---- | --------------------------- | ------------------------------------------------------------ |
| 1    | 顶部修改角色名              | 左侧“我的女朋友”，右侧“我”                                   |
| 2    | 左侧输入“你好啊” → 点击发送 | 中间出现带时间戳的记录                                       |
| 3    | 右侧输入“我爱你” → 点击发送 | 记录自动追加                                                 |
| 4    | 点击“导出为 TXT”            | 得到文件内容：<br>`我的女朋友：`<br>`你好啊`<br>`我：`<br>`我爱你` |

---

## 🗂️ 项目结构

```
chat-record-generator/
├── index.html          # 唯一核心文件（HTML + CSS + JS 三合一）
├── README.md           # 本文档
├── LICENSE             # MIT 许可证
└── assets/             # 可选：预览图、图标等
    └── preview.gif
```

---

## 🛠️ 技术栈

- 原生 HTML5 + CSS3 + ES6（无框架、无依赖）
- 使用 Blob API 实现前端文件下载
- CSS Grid & Flexbox 响应式布局
- 面向对象方式封装业务逻辑（`ChatRecordGenerator` 类）

---

## 📸 预览图

![预览图](./assets/preview.gif)

> 如果 GitHub 未自动播放，可访问 [在线 Demo](https://你的用户名.github.io/chat-record-generator/)

---

## 🤝 参与贡献

1. Fork 本仓库
2. 创建你的功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交变更 (`git commit -m 'Add some AmazingFeature'`)
4. 推送分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

---

## 🐛 报告问题

请前往 [Issues](https://github.com/snareli/chat-record-generator/issues) 页面，按模板描述复现步骤。

---

## 🚧 后续计划

- [ ] 本地 LocalStorage 持久化
- [ ] 多语言支持（i18n）
- [ ] 深色 / 浅色主题切换
- [ ] 消息编辑与删除
- [ ] 时间戳格式自定义

---

## 📄 许可证

MIT © [你的姓名](https://github.com/snareli)  
详见 [LICENSE](./LICENSE) 文件。

---

## 🙏 致谢

灵感来源于日常聊天存档需求，感谢所有提交 Issue 与 PR 的朋友。

---

⭐ 如果本项目帮到你，欢迎点个 Star 支持！