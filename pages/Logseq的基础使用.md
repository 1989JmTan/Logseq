- 基础操作
- 插件安装
- GitHub 同步策略
	- 登录GitHub,创建自己的Logseq仓库
		- 点击[New repository]
		  collapsed:: true
			- ![image.png](../assets/image_1671175508127_0.png){:height 271, :width 560}
		- 在[**Repository name**]输入仓库名称，[**Description**]输入描述，选择pubic或 private
		  collapsed:: true
			- ![image.png](../assets/image_1671175670716_0.png)
		- 获取到Logseq的仓库地址：  https://github.com/1989JmTan/Logseq
		  collapsed:: true
			- ```
			  ssh: connect to host github.com port 22: Connection timed out
			  fatal: Could not read from remote repository.
			  
			  Please make sure you have the correct access rights
			  and the repository exists.
			  ```
	- 安装本地Git
		- Git下载地址:  https://git-scm.com/download/win
		- 安装Git步骤截图
			- 安装路径选择，默认是C盘，但可以自行修改路径
		- 初次运行前配置
			- 查看所有配置
				- ```
				  admin@DESKTOP-0G0C1JA MINGW64 ~
				  $ git config --list
				  diff.astextplain.textconv=astextplain
				  filter.lfs.clean=git-lfs clean -- %f
				  filter.lfs.smudge=git-lfs smudge -- %f
				  filter.lfs.process=git-lfs filter-process
				  filter.lfs.required=true
				  http.sslbackend=openssl
				  http.sslcainfo=D:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
				  core.autocrlf=true
				  core.fscache=true
				  core.symlinks=false
				  pull.rebase=false
				  credential.helper=manager
				  credential.https://dev.azure.com.usehttppath=true
				  init.defaultbranch=master
				  user.name=Jim Tan
				  user.email=jm.tan@outlook.com
				  credential.helper=wincred
				  gui.recentrepo=D:/Program Files/Python2020/This is my python
				  
				  admin@DESKTOP-0G0C1JA MINGW64 ~
				  
				  ```
				- ![image.png](../assets/image_1671189857513_0.png)
			-
	- 进行数据同步
-
-