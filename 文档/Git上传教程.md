# Git命令上传到Gitee教程


## 前提条件
- 已安装Git
- 已创建Gitee仓库并获得仓库地址

## 步骤

### 1. 初始化本地Git仓库
```bash
cd prototype
git init
```

### 2. 添加所有文件
```bash
git add .
```

### 3. 提交到本地
```bash
git commit -m "初始提交：探测分包撮合平台原型"
```

### 4. 连接远程仓库
```bash
git remote add origin https://gitee.com/您的用户名/仓库名.git
```

### 5. 推送到Gitee
```bash
git push -u origin master
```

## 优势
- ✅ 一次性上传所有文件和文件夹
- ✅ 保持完整的目录结构
- ✅ 后续更新方便（只需git push）

