## 基本操作
# 初始化git仓库
```
git init
```

# 查看状态
```
git status
```

# 添加修改
```
git add .
git add 文件名
```

# 反应与上次的不同
```
git diff
```

# 撤销上次更改
```
git reset
```

# 提交相关信息
```
git config --global user.name "名字"     设置写代码人信息
git config --global core.editor 编辑器名 更改编辑器
```

# 提交修改
```
git commit -m "描述信息"
git commit 直接打开对应系统编辑器
```

# 不想让git帮管理的文件
```
vim .gitignore 然后添加目标文件名
```

# 让git不再追踪
```
git rm --cached 文件名
```

## 分支
# 创建分支
```
git branch 分支名
git branch 显示分支
```

# 删除分支
```
git branch -d 分支名
```

# 切换分支
```
git checkout 分支名
```

# 合并分支
在主分支下 
```
git merge 分支名
```

# 提交项目更改到网上
```
git remote add origin 网站
git remote set-url origin 网址
提交更改到网上
ssh-keygen -t rsa -C "你的邮箱名" 创建密钥
git push --set-upstream origin 分支
保存密码
git config credential.helper store 
```

# 复制git仓库
```git clone 网址
```

# 看项目最新进展
```
git pull
```