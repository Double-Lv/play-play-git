## 创建仓库
首先我们要现在远程创建好仓库，以github为例，点new repository填好相关信息就行了。拿到仓库的地址，比如我的是git@github.com:Double-Lv/play-play-git.git

然后就是本地操作了，先在本地建好文件夹play-play-git，新建一个文件比如a.js，然后依次执行以下命令：

1. `git init //初始化，本地生成.git目录`
2. `git add a.js //添加文件到本地暂存区`
3. `git commit -m "新增文件" //提交文件到本地仓库`
4. `git remote add origin git@github.com:Double-Lv/play-play-git.git //添加远程仓库源`
5. `git push -u origin master //push代码到远程仓库，同时设置默认跟踪master分支`

master是git默认创建的分支，也就是我们的主干分支。这样一个仓库就建好了，你已经能在远程仓库中看到a.js。