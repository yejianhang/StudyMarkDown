## **GIT操作**
> clone,提交操作

## 上传
- 创建仓库repository
- 进入文件夹路径，把github上面的仓库克隆到本地

		git clone https://github.com/CKTim/BlueTooth.git

- 这个步骤以后你的本地项目文件夹下面就会多出个文件夹，该文件夹名即为你github上面的项目名，如图我多出了个Test文件夹，我们把本地项目文件夹下的所有文件（除了新多出的那个文件夹不用），其余都复制到那个新多出的文件夹下

- 接着继续输入命令 cd Test，进入Test文件夹
- git add *  
- git commit  -m  "提交信息"  （注：“提交信息”里面换成你需要，如“first commit”）
- git push -u origin master
## COMMIT


- git status： 查看当前状态
- git add .  或者 git add xxx
- git commit -m "注释"、
- git pull <远程主机名> <远程分支名>
- git push <远程主机名> <远程分支名>