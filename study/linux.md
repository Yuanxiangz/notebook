
�鿴Linux�汾��
cat ?/etc/redhat-release



Apt-get update

Apt-get install axel

���أ�
Wget [url]


�ƶ��ļ�/�ļ��У�
Mv [source] [targetfolder]


��ѹ��
Tar -xf [filename]

sudo gunzip catalina.out.2017-12-20.gz



�����ļ�����

find / -name "*booking*"

�ļ�����������
find /home/tujia/logs/kafka-logs -name '*.*' | xargs grep -l '821271331288'

��̬Log��
tail -100f catalina.out

���ļ�
cat catalina.out | grep '111030000857'

-v ������
cat catalina.out | grep '101031000132' | grep -v 'AbstractTask'

��ʾ����5��
grep -C 5 'paySuccessNotify' catalina.out

-A ֮��5��
-B ֮ǰ5��

Head -n 1000 

����tomcat:

[yaohuaz@l-order2.beta.cn2 /home/tujia/tools/bin]$ restart_tomcat.sh /home/tujia/www/tns-order-confirm-app/



�鿴�������߳�����
ulimit -a

�޸��������߳�����
Ulimit -u 65535



����:
sudo cp -rf default-web tns-order-booking-web

ɾ����
rm -rf tns-order-booking-web/

Զ�̿�����
scp /home/space/music/1.mp3 root@www.runoob.com:/home/root/others/music



�鿴����������
df -h

�鿴�ļ���С
 du -h --max-depth=1 ./*

�鿴�ڴ�
cat /proc/meminfo




Curl www.baidu.com


�鿴jvm��ջ��Ϣ
ps -ef | grep booking

top -Hp pid

printf "%x\n" pid2

Jstack pid | grep pid2(0x)


�鿴�˿ڣ�
netstat -anp|grep 80


�����ļ���
find?./ -name test


CFLF�滻ΪLF��
sudo sed -i 's/\r//g' agentupdate.sh


Ȩ�ޣ�

��Ȩ��ִ�У�
sudo chmod u+x file.sh



�鿴����ip:
curl ip.cn



 ����ɾ����
:set nu  ��ʾ�к�

: 31,40d    ɾ��31��40��



jar����ͬ��������˳��ͬ
https://www.cnblogs.com/saaav/p/7716179.html


�޸�yumԴ��
https://www.cnblogs.com/xjh713/p/7458437.html


linux������ʱ��ͬ��
yum?install?-y?ntp????????#��װʱ��ͬ�����������
ntpdate?us.pool.ntp.org???#����ͬ��������
Date


Awk:
cat catalina.out|grep 'esQuery cost time' | awk -F ': '  '{print $2}'


��ʱ����
crontab -e
tail -f /var/spool/mail/yuanxiangz
