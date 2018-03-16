
# 安装git工具
sudo apt-get install git

# 创建公钥 ,一路回车就行
ssh-keygen
# 查看公钥(默认路径)
cat ~/.ssh/id_rsa.pub

# 将公钥加入到github的ssh key里面
https://github.com/settings/keys

# 把仓库的代码克隆到本地
## git clone git@github.com:tsuibin/firstapp.git 

# 进入你的项目目录
## cd firstapp 

# 创建hello.c文件,编写你的代码
## vim hello.c 

# 把hello.c文件加入到待提交列表
## git add hello.c 

# 提交到本地仓库，并注释
## it commit -m"创建了hello.c文件" 

# 把本地仓库的最新代码推送到线上服务器（例如 github）
## git push 

