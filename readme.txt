Git is version control system.
Git is free software.

# 创建git
$ git config --global user.name "baimoc"
$ git config --global user.email "stoneing1314@163.com"

# 创建工作区
$ git init

# 添加文件
$ git add readme.txt
$ git add readme1.txt
$ git commit -m "add 2 file."

# 查看工作区
$ git status

# 查看修改内容
$ git diff

# 版本穿越用法
$ git log
$ git reset --hard HEAD
$ git reset --hard HEAD^
$ git reset --hard HEAD^^
$ git reset --hard HEAD^98
$ git reset --hard yourlogid(in log)
$ git reflog

# 生成SSH Key
$ ssh-keygen -t rsa -C "stoneing1314@163.com"
#目录中: id_rsa id_rsa.pub

# 推送本地
$ git remote add origin git@github.com:baimoc/firstgit.git
# 第一次推送
$ git push -u origin master
# 之后的推送
$ git push origin master
