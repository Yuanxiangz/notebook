Spark all:
http://blog.csdn.net/stark_summer/article/category/2813467


Spark core:
http://blog.csdn.net/stark_summer/article/details/42833609

Spark RDD:
http://blog.csdn.net/stark_summer/article/details/47252619

Spark streaming:
http://blog.csdn.net/stark_summer/article/details/47252619



如何部署
http://www.tuicool.com/articles/QBRJnen



部署成功镜像
Ubuntu:spark
进入镜像需要运行
Source /etc/profile


启动ssh

/etc/init.d/ssh start

Ssh localhost   (密码是: 111111)

启动Spark
$SPARK_HOME/sbin/start-all.sh


测试Spark是否安装成功：
$SPARK_HOME/bin/run-example SparkPi
得到结果：
Pi is roughly 3.14716
