# idea编译zookeeper
* 1、下载ant，配置环境变量  
* 2、从github上pull zookeeper源码  
* 3、进入build.xml所在目录，执行ant eclipse命令  
* 4、导入idea，new->project from existing source，选择导入类型为eclipse
* 5、复制conf下的zoo_sample.cfg，修改为zoo.cfg，并修改里面的dataDir  
* 6、启动org.apache.zookeeper.server.quorum.QuorumPeerMain  
![](https://upload-images.jianshu.io/upload_images/5000473-41e072a6640d58a4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
* 7、启动客户端连接
