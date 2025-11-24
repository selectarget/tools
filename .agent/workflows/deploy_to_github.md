---
description: How to deploy the tools to GitHub Pages
---

# Deploy to GitHub Pages

Follow these steps to host your tools at `https://<YOUR_USERNAME>.github.io/tools/`.

## 1. Initialize Git (Local)
Since this is a new project, we need to initialize git first.

```powershell
git init
git add .
git commit -m "Initial commit: Cyber Security Tools"
```

## 2. Create Repository on GitHub
1. Log in to [GitHub](https://github.com).
2. Click the **+** icon in the top right and select **New repository**.
3. **Repository name**: `tools` (This is important for the URL structure).
4. **Public/Private**: Public (required for free GitHub Pages).
5. Do **not** initialize with README, .gitignore, or License (we have them locally).
6. Click **Create repository**.

## 3. Push Code to GitHub
Replace `<YOUR_USERNAME>` with your actual GitHub username in the command below.

```powershell
# Link your local repo to the remote GitHub repo
git remote add origin https://github.com/<YOUR_USERNAME>/tools.git

# Rename branch to main
git branch -M main

# Push the code
git push -u origin main
```

## 4. Configure GitHub Pages
1. Go to your repository settings on GitHub (`https://github.com/<YOUR_USERNAME>/tools/settings`).
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4. Under **Branch**, select **main** and folder **/(root)**.
5. Click **Save**.

## 5. Access Your Site
Wait a minute or two for the build to finish. Your site will be live at:
`https://<YOUR_USERNAME>.github.io/tools/`
