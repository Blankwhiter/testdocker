# docker 关联github仓库自动构建测试
docker 关联github账号在此就不再赘述了，请参考网上教程。
该项目只是进行测试用自己编写的镜像文件将一个github上的一个jar包用docker部署自动部署。

![关联github仓库](https://img-blog.csdnimg.cn/20200521163434673.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2JlbG9uZ2h1YW5nMTU3NDA1,size_16,color_FFFFFF,t_70)

可以看到 图中 我选的到github仓库对应的位置 
```
/test01/Dockerfile
```


然后我的dockefile文件也选取对应的jar包文件 （github仓库位置 /test01/jar/zookeeper-admin-java.jar）
```
ADD /test01/jar/zookeeper-admin-java.jar /jar/zookeeper-admin-java.jar
```
