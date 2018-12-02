# sshping

## 作用

测试ssh的延时

## 安装

需要python3，以及paramiko库。

centos7下需要
'''
yum install -y python34 python34-pip
'''

安装好以后用
'''
pip3 install paramiko
'''
安装paramiko

## 使用

然后切到测试用户下，运行./sshping [-p PORT] ip即可，我偷懒没写sshkey的参数，默认会使用~/.ssh/id_rsa作为默认私钥
