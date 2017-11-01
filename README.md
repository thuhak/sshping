# sshping

## 作用

据用户反应，jenkins在ssh连接时候会出现连接失败的情况，导致任务失败。
为了调试这个问题，我写了一个sshping的工具来观察这个现象。

## 安装

需要python3，以及paramiko库。

centos下需要
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
