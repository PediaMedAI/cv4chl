# AI4CHL Website - GitHub Pages Version

ICLR 2025 Workshop on AI for Children

## 📁 文件说明

这个项目已经清理完毕，只保留必要的文件：

- **`cv4chl/`** - 完整的网站文件，准备部署到 GitHub Pages
- **`GitHub部署完成说明.md`** - 详细的部署说明
- **`.gitignore`** - Git忽略文件配置

## 🚀 部署到 GitHub Pages

### 快速部署（3步）

1. **创建GitHub仓库**
   - 仓库名：`cv4chl`
   - 组织：`pediamedai`

2. **上传代码**
   ```bash
   cd cv4chl
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/pediamedai/cv4chl.git
   git push -u origin main
   ```

3. **启用GitHub Pages**
   - Settings → Pages
   - Source: Branch `main`, Folder `/ (root)`

### 网站地址

部署完成后访问：**https://pediamedai.github.io/cv4chl/**

## 📝 详细说明

查看 `GitHub部署完成说明.md` 了解：
- 详细的部署步骤
- 如何修改网站内容
- 如何添加新内容
- 常见问题解答

## 🎯 网站结构

```
cv4chl/
├── index.html              # 首页 (About)
├── callforpapers/          # 征稿页面
├── organizers/             # 组织者页面
├── schedule/               # 日程页面
└── assets/                 # 所有资源文件
    ├── css/               # 样式
    ├── keynote/           # 主讲嘉宾照片
    ├── organizer/         # 组织者照片
    ├── panelist/          # 讨论嘉宾照片
    ├── sponsor/           # 赞助商logo
    └── volunteer/         # 志愿者照片
```

## ✨ 特点

- ✅ 纯HTML+CSS，无需构建工具
- ✅ 所有链接指向 `pediamedai.github.io/cv4chl`
- ✅ 导航和图片路径已修复
- ✅ 只包含4个核心页面
- ✅ 准备好直接部署

## 📚 更多信息

- **英文说明**: `cv4chl/README.md`
- **中文详细说明**: `cv4chl/部署说明.md`
- **部署指南**: `GitHub部署完成说明.md`

