# 博客静态资源

静态资源仓库，由 [Hexo](https://hexo.io/) 驱动构建并托管在 GitHub Pages 上。

## 🛠 技术栈

- **框架**: [Hexo 3.8.0](https://hexo.io/)
- **主题**: [Icarus](https://github.com/ppoffice/hexo-theme-icarus)
- **部署**: [GitHub Pages](https://pages.github.com/)
- **评论系统**: Valine
- **看板娘**: Live2D (Hijiki)

## 🚀 本地预览

### 基于 Hexo 构建后预览

```bash
hexo server
```

### 本地静态服务器预览

> 建议使用静态服务器进行本地快速预览

#### 方法 1: 使用 Node.js (http-server)
```bash
npx http-server . -p 8080
```

#### 方法 2: 使用 Python（Mac 自带）
```bash
# Python 3.x
python3 -m http.server 8080
```

运行后访问 [http://localhost:8080](http://localhost:8080) 即可。

## 📄 许可

本项目内容采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可协议。

