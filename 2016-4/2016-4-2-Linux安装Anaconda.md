注意:以下操作以root身份进行
####1.下载安装包
到http://continuum.io/downloads.html下载sh安装包,这里下载的是Anaconda2-4.0.0-Linux-x86_64.sh
####2.执行安装
`./Anaconda2-4.0.0-Linux-x86_64.sh`
####3.修改/etc/profile:
`export PATH="/home/username/anaconda/bin:$PATH`
####4.修改~/.bash_profile
如果`PATH=$PATH:$HOME/bin`则需要改成如下： 
`PATH=$PATH:$HOME/bin:/sbin:/usr/bin:/usr/sbin`
如图:
![](http://7xqhly.com1.z0.glb.clouddn.com/hkl.png)
立即生效:

`source ~/.bash_profile /etc/profile`

`sudo mv /usr/bin/python /usr/bin/python.bak`

`sudo ln -s /home/kcetry/anaconda2/bin/python2 /usr/bin/python`

