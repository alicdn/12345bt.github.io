# centos

傻瓜式一键替换yum源,5条命令 分5次在ssh里面输入
    
# wget -qO- 12345bt.github.io/yum.sh | bash


一键检测服务器配置、IO、下载速度

# wget -qO- 12345bt.github.io/cesu.sh | bash

# 一键开启bbr加速

wget --no-check-certificate 12345bt.github.io/bbr.sh

chmod +x bbr.sh

./bbr.sh

另外的也有人提到用 pip-review ，不想安装就没用
使用方法,也是非常傻瓜一键更新pip库

 安装pip-review

# pip install pip-review

一键升级已安装pip库到最新版本，需要升级的按Y  不需要更新的按N

# pip-review --local --interactive

