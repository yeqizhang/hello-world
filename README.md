# hello-world
my first repository in github

1.测试其它分支修改README.md然后合并到主分支.

  readme-edits分支 下加的(这句话是用readme-edits分支加的，然后合并到master分支)
  
  再次加(这句话是用readme-edits分支加的，然后合并到master分支)

2.创建notgh-pages，测试了不能被选择部署为github pages.

3.创建gh-pages,测试了能够被选择部署为github pages.

4.在master branch下创建/docs文件夹，在里面创建index.html文件，这个文件夹可以被部署到github pages.

5.在 notgh-pages 分支下同步更新master修改的内容，使用“New pull request”按钮，选择base为notgh-pages分支compare master分支.

6. `git reset` 本地回滚

![tortoise的gitlog日志操作reset](http://yeqizhang.github.io/hello-world/pics/gitlog_reset.png)


使用 `git revert` .相当于反向commit。revert 是回滚某个 commit ，不是回滚“到”某个。

先本地revert回滚某个commit，然后push到远程即可实现 **远程回滚** 

测试revert. 20200410 17:18


原来：

![](http://yeqizhang.github.io/hello-world/pics/commit_1_2.png)

![](http://yeqizhang.github.io/hello-world/pics/gitlog_revert.png)

![](http://yeqizhang.github.io/hello-world/pics/commit&push_remote.png)

![](http://yeqizhang.github.io/hello-world/pics/github_status.png)



