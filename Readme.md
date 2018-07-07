## GIT

1. git status

   > 查看哪些文件有没有被跟踪到,提到暂存区中

2. git add

   > git add . 添加所有文件进入暂存区
   >
   > git add filename 添加指定一个文件进入暂存区

3. git diff

   > git diff 查看所有文件内容的修改记录
   >
   > git diff filename 查看指定文件的修改记录

4. git show

5. git log

   > 显示提交历史

6. git reset

   > git reset --hard e377f60e28c8b84158(回滚到指定的提交历史版本上 **注意:** *这会删除回滚到的这个commitID之后所有的提交历史.之前的历史还有* )

7. 修改提交历史中的作者邮箱信息

   > git rebase -i HEAD~2  (进入最新2次提交的历史信息中)

8. git分支

   > git branch (查看分支)
   >
   > git checkout -b iss5 (创建新分支并切换到iss5分支)
   >
   > git branch iss5 (创建iss5的新分支)
   >
   > git checkout iss5 (切换到iss5的分支)
