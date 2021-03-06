# Git 建立远程仓库 - 配置个人信息
- `git config --global user.name "zhukai"`
- `git config --global user.email "zhukai_1998@163.com"`
- 查看是否配置成功`git config -l`

# 创建 SSH Key
- `ssh-keygen -t rsa -C 'zhukai_1998@163.com'` 一直回车就好，直到该命令结束

# 绑定 github 上的 SSH Key
- 拷贝 `~/.ssh/id_rsa.pub`的内容
- 粘贴在 github - setting - SSH and GPG keys
- `ssh -T git@github.com` 测试是否绑定成功，如出现以下信息，则成功<br>
`Hi zhukai1998! You've successfully authenticated, but GitHub does not provide shell access.`

# git 本地配置
- 初始化 `git init`
- 添加远程仓库 `git remote add origin git@github.com:xxx.git`
- 添加到暂停区（索引） `git add <file>` 或者 `git add .` 添加全部
- 提交到仓库：`git commit -m "备注"`
- 推送文件到仓库 `git push -u origin master`

# 编辑 github 的文件名
- 首先我们将整个仓库clone到本地 `git clone url`
- cd 仓库
- `git init`
- `git rm / rm -r / mv filename`
- `git commit -m "log message"`
- `git push origin master`

# 新建仓库
- 在 Github 上 new 一个仓库
- 将该仓库clone到本地 `git clone url`
- 用 IDEA 根据下载好的仓库文件夹新建一个项目
- cd 仓库
- `git init`
- `git add filename`
- `git commit -m "log message"`
- `git push origin master`

# 删除本地仓库
- 删除本地仓库隐藏文件 .git 即可，之后便可以删除本地仓库
