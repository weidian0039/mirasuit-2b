# MIRASUIT 2B 官网 - 部署指南

## 方法：GitHub Pages（推荐，免费）

### 步骤 1：创建 GitHub 仓库

1. 在 GitHub 上创建一个新仓库，命名为 `mirasuit-2b`
2. 不要初始化 README

### 步骤 2：推送代码

在终端执行（替换 `YOUR_USERNAME` 为你的 GitHub 用户名）：

```bash
cd /Users/dianmacpromax/SynologyDrive/_claude_work/projects/MIRASUIT/mirasuit-2b-standalone

git add index.html
git commit -m "Initial commit: MIRASUIT 2B website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/mirasuit-2b.git
git push -u origin main
```

### 步骤 3：启用 GitHub Pages

1. 打开仓库的 Settings → Pages
2. Source 选择：Deploy from a branch
3. Branch 选择：main
4. Folder 选择：/(root)
5. 点击 Save

### 步骤 4：访问网站

几分钟后，你的网站将上线：
```
https://YOUR_USERNAME.github.io/mirasuit-2b/
```

---

## 当前状态

✅ 代码完成：`index.html`
✅ Git 仓库已初始化：`mirasuit-2b-standalone/`
⏳ 等待：推送到 GitHub + 启用 GitHub Pages

---

## 备选方案：Netlify Drop

1. 打开 https://app.netlify.com/drop
2. 将 `index.html` 拖进去
3. 几秒钟后获得一个 `https://xxx.netlify.app` 网址

---

## 本地预览

直接在 Finder 中双击 `index.html` 即可在浏览器中预览。
