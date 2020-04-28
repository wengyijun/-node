# -阿里云配置node.js

登录并连接ECS实例。
进入home目录下来安装，可以自定义选择安装的目录
sudo apt-get update
apt-get install git
[root@iZuf66ntz ~]# cd /home
下载nodejs的linux版文件安装Node.js。

下载Node.js安装包。
wget https://nodejs.org/dist/v10.15.3/node-v10.15.3-linux-x64.tar.xz
解压文件。
tar xvf node-v10.15.3-linux-x64.tar.xz
创建软链接，您就可以在任意目录下直接使用node和npm命令。
ln -s /home/node-v10.15.3-linux-x64.tar.xz/bin/node /usr/local/bin/node
ln -s /home/node-v10.15.3-linux-x64.tar.xz/bin/npm /usr/local/bin/npm
查看node、npm版本。

curl -sL https://deb.nodesource.com/setup_13.x | sudo -E bash -
sudo apt-get install -y nodejs

node -v
npm -v
安装完毕


































