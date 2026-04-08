# 朋友圈生成器 - 网页版部署指南

## 文件结构

```
web-moments-generator/
├── index.html              # 主页面（直接双击即可本地使用）
├── assets/
│   ├── html2canvas.min.js  # 截图依赖库
│   ├── 我的头像.png         # 默认头像
│   └── 默认背景图.JPG       # 默认封面图
└── DEPLOY.md               # 本文档
```

## 使用方式

### 方式一：直接本地使用（最简单）
直接双击 `index.html` 打开即可使用，所有功能完全正常。

### 方式二：分享给朋友（推荐）

#### 1. 上传到 GitHub Pages（免费）

1. 注册/登录 [GitHub](https://github.com)
2. 新建一个 Repository，名称随意（如 `moments-generator`）
3. 把 `web-moments-generator` 文件夹内的所有文件上传到这个仓库
4. 进入 **Settings → Pages**，Source 选择 `main` branch 和 `/ (root)`
5. 等待 1-2 分钟，你的网页就上线了！
   - 访问地址：`https://你的用户名.github.io/moments-generator/`

#### 2. 上传到 Netlify（免费，无需 Git）

1. 打开 [app.netlify.com/drop](https://app.netlify.com/drop)
2. 直接把 `web-moments-generator` 文件夹拖进去
3. 几秒后获得一个随机网址，可以自定义子域名

#### 3. 上传到 Vercel（免费，无需 Git）

1. 打开 [vercel.com](https://vercel.com)
2. 用 GitHub 登录或注册
3. 点击 "Add New" → "Static Site"
4. 上传文件夹，等待部署完成

## 功能说明

- ✅ 编辑个人信息（昵称、头像、封面图）
- ✅ 添加/编辑/删除朋友圈动态
- ✅ 支持 1-9 张配图
- ✅ 评论和点赞功能
- ✅ 状态栏时间和信号文字可自定义
- ✅ 封面背景颜色预设 + 自定义颜色选择器
- ✅ 一键生成高清长截图并下载

## 注意事项

- 截图文件名为 `朋友圈_时间戳.png`
- 所有数据都在本地处理，不上传任何服务器，隐私安全
- 建议使用 Chrome/Edge/Safari 等现代浏览器
