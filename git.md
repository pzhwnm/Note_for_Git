# git 操作记录

### git add/rm + file

告诉git要新追踪(或删除)的文件

### git commit -m "message"

确认所有已追踪文件的提交, 创建快照，确认修改

**Note:注意是所有文件，所以最好git add一个，commit一下，避免一次性提交太多文件，当一个文件出问题的时候，就得重新搞，很麻烦**

### git status

查看待提交状态，包括哪些文件是还没被要求去追踪的，哪些是等待commit的，哪些是被修改的

### git push

提交到代码仓库

### git log

查看提交历史

### git diff

查看你的修改到底修改了哪里

### git pull

拉取最新一版的代码

如果两个人同时修改文件，第二个人的push就会失败

那么对于第二个人的具体做法就要先git stash保存本地代码到暂存区

再git pull

在暂存区拉出

git stash pop

具体参考：

https://zhuanlan.zhihu.com/p/403557624

