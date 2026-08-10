# 工作台 - 在线版部署包

## 文件列表
- index.html - 主页面
- manifest.json - PWA 配置
- sw.js - 服务工作者
- server.js - Node.js 服务器
- start.bat - Windows 启动脚本
- README.md - 使用说明
- icon.svg - 应用图标

## 快速开始

### 方式一：本地运行
```bash
# 1. 确保已安装 Node.js
node --version

# 2. 双击 start.bat 启动
# 或命令行运行：
node server.js

# 3. 获取电脑 IP（cmd: ipconfig）
# 4. 手机浏览器访问：http://电脑IP:8080
```

### 方式二：免费部署到 GitHub Pages
```bash
# 1. 创建 GitHub 仓库
# 2. 上传此文件夹所有文件
# 3. Settings → Pages → 选择 main 分支
# 4. 访问生成的链接
```

### 方式三：免费部署到 Netlify
```bash
# 1. 注册 netlify.com
# 2. 拖拽整个文件夹到部署页面
# 3. 自动生成访问链接
```

## 手机端使用方法

### Chrome (Android)
1. 访问网站
2. 点击菜单（三个点）
3. 选择"添加到主屏幕"
4. 像 App 一样使用

### Safari (iOS)
1. 访问网站
2. 点击分享按钮
3. 选择"添加到主屏幕"
4. 像 App 一样使用

## 注意事项
- 手机和电脑必须同一 WiFi
- 确保防火墙允许 8080 端口
- 数据存储在浏览器本地

## 跳转说明
抖音和小红书使用官方分享链接格式：
- 抖音：https://v.douyin.com/xxx/
- 小红书：https://www.xiaohongshu.com/explore/xxx

点击链接后会在新标签页打开，可在 APP 内查看完整内容。
