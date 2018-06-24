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

<<<<<<< HEAD
   > git reset --hard e377f60e28c8b84158(回滚到指定的提交历史版本上 **注意:** *这会删除回滚到的这个commitID之后所有的提交历史.之前的历史还有* )
   >
   > 1 2 
   > =======
   > git reset --hard e377f60e28c8b84158(回滚到指定的提交历史版本上 **注意:** *这会删除回滚到的这个commitID之后所有的提交历史.之前的历史还有* )
   > >>>>>> 8181d2bf93e300a38abb5eed2c41e7a2e3ad7474
