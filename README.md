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
