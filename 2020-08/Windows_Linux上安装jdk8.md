# 1.准备
官网下载jdk8，或者由以下网盘提供的jdk
jdk8
链接：https://pan.baidu.com/s/1oGp0PgaiwkkiToGCK5c7GA 
提取码：3xdf
<img src="https://img-blog.csdnimg.cn/c8ff3eca16834b8fb01a45e639920431.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>

# 2.Windows安装Java

<img src="https://img-blog.csdnimg.cn/cb05ab2027ab4b6eb209c50346e1f1d1.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>

<img src="https://img-blog.csdnimg.cn/9c6d43e9ea504e8d97e7a9a1dbd06353.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>


<img src="https://img-blog.csdnimg.cn/acf6673c734f42b1aebb6974891c3ba7.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>


<img src="https://img-blog.csdnimg.cn/67ac806bf45a4afe8d5b644e61e00a82.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>

配置环境变量

<img src="https://img-blog.csdnimg.cn/936d1e2bfc964b25807d97bd5a957682.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>

<img src="https://img-blog.csdnimg.cn/010e335431ca435d86bb614fd8202e34.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>


<img src="https://img-blog.csdnimg.cn/2e0b55cd5f554c0793b50592279dbd13.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>

<img src="https://img-blog.csdnimg.cn/6693f2eef52a4fc29839d1f42e61920d.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>

验证是否安装完成
重新打开命令行窗口，输入以下命令验证

```bash
java -version
```

<img src="https://img-blog.csdnimg.cn/03a4f4aa9f20401c91226d084ad9624d.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>
# Linux上安装Java
将下载好的jdk解压到安装目录
```bash
 tar -xzvf jdk-8u141-linux-x64.tar.gz
```
编辑配置文件

```bash
vi /etc/profile
```

```bash
JAVA_HOME=安装包的解压路径
export PATH=$PATH:$JAVA_HOME/bin
```

<img src="https://img-blog.csdnimg.cn/c91706e6d3eb48ecb023f045af6ea6d5.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>


<img src="https://img-blog.csdnimg.cn/60a1ec482850487cb09f46adc171f982.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2FfaHVpX3RhaV9sYW5n,size_16,color_FFFFFF,t_70#pic_center" width="80%"/>
验证是否安装完成

```bash
java -version
```
