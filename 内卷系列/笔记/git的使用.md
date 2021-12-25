* 版本控制

  - `GIT` 分布式版本控制系统,没有中央服务器.
  - `SVN` 集中式版本控制系统,有中央服务器.
  - `CVS`
  - `VSS`
  - `TFS`

* Git 环境配置

  * 下载官网 `https://git-scm.com/download/win` 这个下载慢,所有东西下载慢的话找镜像下载

  * 淘宝镜像下载地址`http://npm.taobao.org/mirrors/git-for-windows/`

    * 问题:`1.淘宝镜像下载,能下哪些?`

      ​        `2.镜像是什么玩意`

  * 安装:无脑下一步

  * 启动

    ![Image text](..\img\1640225777.jpg)

    * `Git Bash:`  Unix与Linux的风格的命令行,使用最多,推荐最多
    * `Gut CMD:` Windows风格的命令行
    * `Git GUI:` 图形界面的git,不建议初学使用,尽量熟悉常用指令

  * 基本的linux命令

    * `cd` 改变目录

    * `cd..` 回退到上一个目录,直接程度进入默认目录

    * `pwd`显示当前所有路径

    * `ls(ll)`都是列出当前目录中的所有文件,只不过`ll`列出的内容更为详细

    * `touch`新建一个文件 如`touch index.js`就会在当前目录下新建一个`index.js`文件

    * `rm`删除文件,`rm index.js` 就会把`index.js`文件删除

    * `mkdir`新建一个目录,就是新建个文件夹

    * `rm -r` 删除一个文件夹,`rm -r src`删除`src`目录

      `rm -rf` 切勿尝试 递归删除

    * `mv`移动文件,`mv index.html src ` 其中`src`是目标文件夹,这个文件夹必须存在

    * `rest` 重新初始话终端/清屏

    * `clear`清屏

    * `help` 帮助

    * `exit` 退出

    * `#`表示注释

  * `Git`配置

    * `git config -l`查看所有配置![Image text](..\img\1640417894.png)
    
      `这个比较详细,上面的路径是大概能找到安装位子`
    
    * `git config --system --list` 系统给配置的![Image text](..\img\1640418466.jpg)
    
    * `git config --global --list` 全局变量![Image text](..\img\1640418572.jpg)
    
    * 这些配置都是有配置文件的![Image text](..\img\1640418920.jpg)![Image text](..\img\1640419238.jpg)系统配置在,安装路径的gitconfig文件,用户信息在用户下面的gitconfig文件中
    
    * 设置用户信息用指令完成 `git config --global user.name "xxxx"` 设置账号 ,`git config --global user.email "xxxx"` 这是邮箱,`当然我猜可以改配置文件 我没事试过`

* Git 基本理论

  * 工作目录(`Working Directory`)
* 暂存区(`Stage/Index`)
  
  * 资源库(`Repository`或`Git Directory`)
* 远程`git`仓库(`Remote Directory`)
  * 提交

    * `git add files` 加入文件 从`Working Directory` 上传到 `Stage/Index`
    * `git commit` 从`Stage/Index` 上传到 `History`
    * `git push` 从`History`上传到`Remote Directory`
 * 下载
  
    * `git pull`  从`Remote Director`下载到`History`
    
    * `git reset` 从`History`更新到`Stage/Index` 
    
    * `git checkout`  从`Stage/Index` 更新到`Working Directory` 
    
    * 这是分支![Image text](..\img\1640420987.jpg)
    
* Git 项目搭建(两种方法)

    * `git init` 创建一个新的代码库(注:这种方法我不知道怎么上传到`github`)

    * `git clone [url] git@github.com:CainHJ/studyNotes.git`  在`github`找到clone地址直接克隆![Image text](..\img\1640422045.jpg)

* Git 文件操作

* 使用码云

* IDEA中集成Git

* 说明:Git分支