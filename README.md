# 自习室 — Study Room

一个极简唯美的在线自习室，采用 Apple 玻璃风格（Glass Morphism）设计。

## ✨ 功能

- **🎨 场景切换**：图书馆、咖啡馆、森林、雨天窗边 — 4 种高清背景，平滑过渡
- **🎵 背景音乐**：Lofi、钢琴、雨声、壁炉、海浪 — 5 种混搭音效
- **⏱ 番茄钟 & 倒计时**：
  - 番茄钟模式（可自定义专注/休息时长）
  - 自定义倒计时模式
  - 可视化环形进度条
  - 时间到自动提醒 + 阶段自动切换
- **✅ 待办清单**：添加、完成、删除，数据自动保存
- **🕐 实时时钟**：大字体数字时钟

## 🚀 使用方式

### 直接打开
双击 `index.html` 即可在浏览器中使用。

### 部署到服务器
将整个文件夹上传到任意静态托管服务：
- **GitHub Pages**：Push 到仓库，开启 Pages
- **Vercel**：`vercel --prod`
- **Netlify**：拖拽文件夹到 Netlify Drop

### 本地预览
```bash
cd study-room
python3 -m http.server 8080
# 打开 http://localhost:8080
```

## ⌨️ 快捷键

| 按键 | 功能 |
|------|------|
| `Space` | 开始/暂停计时器 |
| `R` | 重置计时器 |

## 🛠 技术栈

- 纯 HTML/CSS/JS，零依赖
- CSS `backdrop-filter` 玻璃拟态效果
- YouTube IFrame API 驱动背景音乐
- Web Audio API 生成提示音效
- localStorage 持久化所有设置

## 🌐 浏览器兼容

- Chrome / Edge 90+
- Safari 15+
- Firefox 90+
- 移动端 Safari / Chrome
