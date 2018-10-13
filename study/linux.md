
查看Linux版本：
cat ?/etc/redhat-release



Apt-get update

Apt-get install axel

下载：
Wget [url]


移动文件/文件夹：
Mv [source] [targetfolder]


解压：
Tar -xf [filename]

sudo gunzip catalina.out.2017-12-20.gz



查找文件名：

find / -name "*booking*"

文件内容搜索：
find /home/tujia/logs/kafka-logs -name '*.*' | xargs grep -l '821271331288'

动态Log：
tail -100f catalina.out

搜文件
cat catalina.out | grep '111030000857'

-v 不包含
cat catalina.out | grep '101031000132' | grep -v 'AbstractTask'

显示附近5行
grep -C 5 'paySuccessNotify' catalina.out

-A 之后5行
-B 之前5行

Head -n 1000 

重启tomcat:

[yaohuaz@l-order2.beta.cn2 /home/tujia/tools/bin]$ restart_tomcat.sh /home/tujia/www/tns-order-confirm-app/



查看最大可用线程数：
ulimit -a

修改最大可用线程数：
Ulimit -u 65535



拷贝:
sudo cp -rf default-web tns-order-booking-web

删除：
rm -rf tns-order-booking-web/

远程拷贝：
scp /home/space/music/1.mp3 root@www.runoob.com:/home/root/others/music



查看磁盘容量：
df -h

查看文件大小
 du -h --max-depth=1 ./*

查看内存
cat /proc/meminfo




Curl www.baidu.com


查看jvm堆栈信息
ps -ef | grep booking

top -Hp pid

printf "%x\n" pid2

Jstack pid | grep pid2(0x)


查看端口：
netstat -anp|grep 80


查找文件：
find?./ -name test


CFLF替换为LF：
sudo sed -i 's/\r//g' agentupdate.sh


权限：

授权可执行：
sudo chmod u+x file.sh



查看外网ip:
curl ip.cn



 批量删除：
:set nu  显示行号

: 31,40d    删除31到40行



jar包不同机器加载顺序不同
https://www.cnblogs.com/saaav/p/7716179.html


修改yum源：
https://www.cnblogs.com/xjh713/p/7458437.html


linux服务器时间同步
yum?install?-y?ntp????????#安装时间同步服务（组件）
ntpdate?us.pool.ntp.org???#设置同步服务器
Date


Awk:
cat catalina.out|grep 'esQuery cost time' | awk -F ': '  '{print $2}'


定时任务：
crontab -e
tail -f /var/spool/mail/yuanxiangz
