## Git

```c++
git add .
git commit -m "添加注释"
git push origin 分支名称，一般使用 git push origin master
```

Git 一般工作流程

1 从远程仓库克隆 Git资源作为本地仓库

2 从本地仓库`checkout`代码到工作区进行代码修改

3 在提交前先将代码提交到暂存区 

`git add .`

4 提交修改，提交到本地仓库，本地仓库中保存各个历史版本 

`git commit -m 注释`

5 修改完毕后，需要共享代码，使用push到远程仓库 

`git push origin master`

---

使用Github搜索相关内容时：

`in:description springboot language:java pushed:>2019-09-03`

`in:readme C++ stars:>3000 `

`in:name springboot+mybais stars:>1000`