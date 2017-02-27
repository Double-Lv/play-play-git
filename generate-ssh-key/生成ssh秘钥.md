## 生成ssh秘钥

首先可以看下本地是否已经存在，在命令行输入`cd ~/.ssh`，查看该目录下是否有id_rsa和id_rsa.pub这两个文件。其中id_rsa.pub就是公钥了，需要你配在github中，或者是其他代码托管仓库。

如果不存在这个文件夹，则运行一下命令生成：

1. `ssh-keygen -t rsa -C lvdabao@163.com //生成秘钥`
2. `ssh -T git@github.com //链接github测试，是否成功` 

如果显示You've successfully authenticated这样的内容，说明成功。
