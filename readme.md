# 1. 初始化本地仓库
git init

# 2. 暂存刚建的 README 文件
git add .

# 3. 提交（如果报 nothing to commit，说明文件没保存，或者没建文件）
git commit -m "docs: 初始化项目"

# 4. 关联刚才复制的 GitHub 地址
git remote add origin https://github.com/你的用户名/你的新仓库.git

# 5. 推送到远程仓库（首次推送必须加 -u）
git push -u origin main