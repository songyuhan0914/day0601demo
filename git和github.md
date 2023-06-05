# day0601demo
城市学院21级web上课教学演示

克隆远程代码到本地
git config --global user.name "你的用户名"
git config --global user.email "你的邮箱"
git clone github项目仓库克隆地址

本地想向github操作文件，需要登陆github，在本地和github配置秘钥，即可直接登录。类似本地和远程都有一把钥匙，每次操作的时候，会对比钥匙，对比成功，允许操作
本地生成密码 ssh-keygen
找到秘钥生成的文件位置，把密钥复制下来，
打开github平台，找到头像下面的settings，找到SSH and GPG keys。 在SSH keys模块点击new SSH key按钮，输入密钥名字，把密钥复制在key模块保存即可

进入本地客隆的项目
写完代码
git status 查看本地仓库的状态
红色文件表示更改的文件
git add . 添加到暂存区
git commit -m '版本信息'
git push   推到github仓库

