# Git 的使用

## Q1

Git 是一个广泛使用的版本管理工具，适合团队开发。  
如果你用过 Git，那么请回忆一下，  
我们在确认开发需求之后，从写代码到提交进团队的代码仓库。  
这个过程中大概会用到哪几条命令？

请直接在这里作答。

答：

    git clone/init
    git add ./<file>
    git checkout -- <file>
    git rm --cached <file>
    git commit -m ''
    git branch
    git branch <分支名>
    git branch -d <分支名>
    git merge <分支名>
    git branch -m <原分支名> <更改的分支名>

## Q2

你知道和用过哪些 Git 的方法论和技巧

答：
提交自己的代码要新建自己的分支再提交