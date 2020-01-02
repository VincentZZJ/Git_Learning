# Git #
----
## 常用命令 ##
+	本地初始化仓库 ---  `git init`
+	查看仓库内文件的状态 ---  `git status`
+	将文件添加到**暂存区** ---  `git add . / git add ReadMe.md`
+	将暂存区文件提交到**本地仓库** ---  `git commit -m "some tips"`
+	查看提交历史 ---  `git log`
+	回退版本
	+	回退上一个版本 --- `git reset --hard HEAD^`
	+	回退到前N个版本 --- `git reset --hard HEAD~n`
	+	回退到指定版本 --- `git reset --hard 版本号`

+	查看提交历史的版本号(对应上面的回退处理)	--- `git reflog`  
	+	![](./img/reset.png)

+	查看文件内容 --- `cat ReadMe.md` 
+	查看文件与上一版本的差异 --- `git diff ReadMe.md`
+	撤销操作 --- `git checkout --ReadMe.md`
	+	已提交到暂存区(则已经`git add`),撤销后则回到暂存区的文件状态
	+	未提交到暂存区，撤销后则回到上一版本的文件状态

+	删除文件 --- `rm ReadMe.md`
	+	若想恢复，则可执行撤销操作


## 题外话 ##
+	往Github上传项目
![](./img/how_to_upload.png)