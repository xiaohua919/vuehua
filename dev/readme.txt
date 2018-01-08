//安装完git设置用户名与邮箱
$ git config --global  user.name  "xx"    //设置用户名

$ git config --global  user.email  "xx@163.com"   //设置邮箱

//git init命令把这个目录变成Git可以管理的仓库：
$ git init
Initialized empty Git repository in 目录

//添加文件到仓库可反复多次使用，添加多个文件
git add readme.txt


//提交到仓库
git commit  -m  "备注说明"


命令可以让我们时刻掌握仓库当前的状态
git status

//查看修改记录
git diff  

//查看提交日志
git  log
//日志显示一行
get  log --pretty=oneline

//回退版本
Git必须知道当前版本是哪个版本，在Git中，用HEAD表示当前版本，也就是最新的提交3628164...882e1e0（注意我的提交ID和你的肯定不一样），上一个版本就是HEAD^，上上一个版本就是HEAD^^，当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100
git reset --hard HARD^

git reset --hard 版本号


//回退文件版本
git  checkout  -- 文件名

//删除文件
//git rm 文件名

//添加远程库 origin远程仓库的名字  项目地址
git remote add origin https://github.com/xiaohua919/vuehua.git

//本地内容推送到远程主目录
git push -u origin  master


//远程库下载到本本地
git clone   地址名

//创建分支 git checkout命令加上-b参数表示创建并切换，相当于以下两条命令：
git checkout -b dev

//查看分支
git brance

