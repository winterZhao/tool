wekan

开源版的trello


#### 安装

    sudo su

    yum makecache fast

    yum install yum-plugin-copr epel-release

    yum copr enable ngompa/snapcore-el7

    yum install snapd

    systemctl enable --now snapd.socket

    snap install wekan

    snap set wekan root-url="http://127.0.0.1:3001"
    snap set wekan port='3001'
    systemctl restart snap.wekan.wekan

#### 更多安装说明

[wekan](https://github.com/blacklabelops/confluence)
