## git-demo文件说明

git --version  // 查看 git 版本

git config --global user.name 提交人姓名     // 配置姓名

git config --global user.email 提交人邮箱     // 配置邮箱

git config --list     // 查看配置信息

通过命令行的形式进行的配置，也可以通过修改配置文件来进行修改，文件名字叫 `.gitconfig`，位置在 C:\Users\系统用户名\\.gitconfig



git init 	// 初始化本地仓库

git status 	 //  查看文件状态

git add 文件名 	// 添加某个文件到暂存区，如果写 .  代表当前文件夹下所有的文件

git commit -m 日志说明     // 提交到本地仓库

git log     // 查看提交记录

git checkout 文件名     // 撤销，让暂存区文件覆盖工作区间文件

git rm --cached 文件名   	// 在暂存区移除相应文件

git reset --hard 提交ID  	// 恢复到指定版本

git branch       // 查看分支

git branch develop     // 创建分支

git checkout 分支名     // 切换分支

git merge 来源分支     // 合并分支

git branch -d 分支名称    // 删除分支

git branch -D 分支名称   // 强制删除

git checkout -b 分支名称    // 创建并切换分支命令

git stash   // 存储临时改动

git stash pop  // 恢复改动

git clone 地址     //  克隆远程仓库

git push 地址 分支名      // 往服务器推送

git pull 地址       // 将服务器代码拉取到本地

git remote add 名称 地址    //  给地址取别名

git push -u origin master      // -u的参数让git记录信息，下次只需要 git push 就能进行提交

ssh-keygen   // 生成一对密钥



git忽略清单文件名称叫： `.gitignore`     在执行`git`命令的时候，`git`就会忽略这些文件
