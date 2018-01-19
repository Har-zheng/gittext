
### Git提交本地工程到服务器
## 提交到本地项目到服务器
# 1.首先在git服务器上创建初始项目，并记录ssh地址
# 2.进入本地项目目录，依次执行下面命令
  ``
     $git init  //初始化本地仓库
		$git add * //或添加需要提交的文件
		$git commit -m "init project" //提交到本地仓库
		$git remote add origin https://github.com/zfy1355/presst-test.git //和远程仓库项目进行关联
		$git push -u origin master //提交到远程仓库
	``		