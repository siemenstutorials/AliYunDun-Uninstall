# AliYunDun-Uninstall
AliYunDun-uninstall
阿里云盾（AliYunDun）卸载
````bash
wget https://raw.githubusercontent.com/siemenstutorials/AliYunDun-Uninstall/master/uninstall.sh
chmod +x uninstall.sh
./uninstall.sh
rm -rf uninstall.sh
````
````bash
wget https://raw.githubusercontent.com/siemenstutorials/AliYunDun-Uninstall/master/quartz_uninstall.sh
chmod +x quartz_uninstall.sh
./quartz_uninstall.sh
rm -rf quartz_uninstall.sh
pkill aliyun-service
rm -fr /etc/init.d/agentwatch /usr/sbin/aliyun-service
rm -rf /usr/local/aegis*
````
最后检查卸载情况——应输出为空：
````bash
ps aux | grep aeg 
````
我的节点供应站
[星际云网络加速](www.xjycloud.xyz)
<div>[我的博客](https://siemenstutorials.github.io/)</div>
