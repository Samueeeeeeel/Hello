# 本地操作
mkdir my-project && cd my-project
git init
echo "# My Project" > README.md
git add . && git commit -m "Initial commit"
git remote add origin https://github.com/[用户名]/my-project.git
git push -u origin main
