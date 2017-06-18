# Demo
## 请每个人都fork一份，然后在自己姓名对应的文件夹下操作
### 使用步骤：

1. 加入 XiyouLinux3plus1-2018 (非必须)
2. fork XiyouLinux3plus1-2018 下的项目
3. 将仓库克隆至本地
4. 进行必要的修改
5. 将本地修改提交至远程端
6. 提交pull request

> 注：3,4,5步骤和操作一般自己的仓库没区别

### 怎样和源仓库内容保持同不呢？
1. $ git remote add 3plus1 git@github.com:XiyouLinux3plus1-2018/Demo.git # 添加源仓库URL并指定将其更新到本地的3plus1分支上
2. $ git fetch 3plus1 # 将源内容拉回到本地 3plus1 分支上
3. $ git checkout master # 切换至主分支，如果原本就为主分支，可忽略
4. $ git merge 3plus1/master # 合并分支，将 3plus1 合并到 master 分支上
5. $ git add ...
6. $ git commit -m "balabala"
7. $ git push origin master

> 注:步骤**1**只需要第一次提交即可，以后可以直接从步骤**2**执行
     步骤 5,6,7 是将本地仓库与远程仓库进行同步
