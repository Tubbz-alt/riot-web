# Riot.im
A SlackBuild for Riot.im

一种新型的“邦联式”通讯工具(Matrix 协议)。特点：

	- 邦联化，一改当前主流的中心化架构，使用者可以搭建自己的 Matrix服务器提供服务，即可用于团队之间交流，又可与其他 Matrix 服务器串通。因此也可以通过变换服务器（ip）来躲避GFW的封锁。


## Usage

下载 官方 Riot.im 安装包(riot-web)，到本 git 目录下。地址在 riot.info 里就有。

```
cd riot-web/

source ./riot.info

wget -c $DOWNLOAD
```

以 root 身份运行安装脚本：

	# ./riot.SlackBuild

软件会被装到 /opt 下。
