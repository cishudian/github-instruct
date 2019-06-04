# github-instruct
参考网页链接 https://my.oschina.net/bxxfighting/blog/378196

ssh-keygen -t rsa -C "2565724815@qq.com"

//配置用户
git config --global user.email "2565724815@qq.com"
git config --global user.name "cishudian"

//初始化
git init
//对软件管理
git remote add origin git@github.com:cishudian/ros_message.git

//添加所有文件
git add .

//添加指定文件
git add xx
//添加注释
git commit –m “注释”
//上传文件
git push git@github.com:cishudian/ros_message.git
//数据不能上传
git pull --rebase origin master
//上传
git push git@github.com:cishudian/ros_message.git
git push origin master

//参考以下文章
https://blog.csdn.net/qq_29985391/article/details/85047841

git remote add origin**************
fatal: remote origin already exists（报错远程起源已经存在。）
git remote rm origin
git remote add origin

