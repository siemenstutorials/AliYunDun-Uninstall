# AliYunDun-Uninstall
AliYunDun-uninstall
阿里云盾（AliYunDun）卸载
wget https://raw.githubusercontent.com/siemenstutorials/AliYunDun-Uninstall/master/uninstall.sh
chmod +x uninstall.sh
./uninstall.sh
rm -rf uninstall.sh

wget https://raw.githubusercontent.com/siemenstutorials/AliYunDun-Uninstall/master/quartz_uninstall.sh
chmod +x quartz_uninstall.sh
./quartz_uninstall.sh
rm -rf quartz_uninstall.sh
pkill aliyun-service
rm -fr /etc/init.d/agentwatch /usr/sbin/aliyun-service
rm -rf /usr/local/aegis*
检查卸载情况：
ps aux | grep aeg 

我的节点供应站
[星际云网络加速](www.xjycloud.xyz)
