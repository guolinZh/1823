<!--注册的名  -->
$git config --global user.name "guolinZh"
<!-- 注册的邮箱 -->
$git config --global user.email "2390507929@qq.com"


<!-- git初始化  一个项目初始一次
-->

<!-- ls -a 查看是否存在隐藏文件夹（蓝色的）.git  表示成功 当前文件夹下所有的文件夹 -->

git 本地索引添加


$ git add -A  表示添加所有

$ git status 查看状态

如果你添加的文件夹全绿那么表示add没有问题

git 工作区放入仓库之中  add -A
 $ git commit -m "第一次提交"

git commit -m“first commit” 
git remote add origin https://github.com/guolinZh/1823.git
 git push -u origin master