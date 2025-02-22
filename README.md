# GitSkills
Git学习实践项目：从零开发，最好的方式是先创建远程库，然后从远程库克隆。

给项目添加.gitignore
.gitignore可以忽略你不想上传的文件

清除已经上传的多余文件
如果你添加.gitignore的时候，git里面已经上传了很多不需要的文件，则使用下面两个命令干掉他们
如果是文件夹：git rm -r --cached 文件夹名
如果是文件：git rm --cached 文件名
方法参考自：https://stackoverflow.com/questions/9550437/how-to-make-git-ignore-idea-files-created-by-rubymine