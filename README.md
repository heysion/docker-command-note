# Docker 安装

openSUSE 12.3

    $ sudo zypper ar -f http://download.opensuse.org/repositories/Virtualization/openSUSE_12.3/ Virtualization

    $ sudo rpm --import http://download.opensuse.org/repositories/Virtualization/openSUSE_12.3/repodata/repomd.xml.key

openSUSE 13.1

    $ sudo zypper ar -f http://download.opensuse.org/repositories/Virtualization/openSUSE_13.1/ Virtualization

    $ sudo rpm --import http://download.opensuse.org/repositories/Virtualization/openSUSE_13.1/repodata/repomd.xml.key

安装

    sudo zypper in docker

添加Docker 后台进程

    $ sudo systemctl start docker

添加开机启动

    $ sudo systemctl start docker

添加用户组到docker组

    sudo usermod -a -G docker <username>

Reference Links

    docs.docker.com/installation/openSUSE/
    docs.docker.com/installation/


