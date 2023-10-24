# GitHub Quick Setup
```shell
# create a new repository on the command line
echo "# python_cookbook" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/cooperwang-github/python_cookbook.git
git push -u origin main

#  push an existing repository from the command line
git remote add origin https://github.com/cooperwang-github/python_cookbook.git
git branch -M main
git push -u origin main
```