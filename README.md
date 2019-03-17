# Javaweb-firstcup-war
java web course study example

1.先决条件：
maven3.6
glassfish5
jdk1.8+
2.本地运行
首先克隆本仓库到本地并解压
```
git clone https://github.com/Love-LG/Javaweb-firstcup-war.git
```
cd到解压文件的pom.xml目录下使用maven将其打包生成.war文件
```
mvn package

```
cd到glassfish安装目录的bin目录下使用以下命令启动glassfish和和glassfish的database服务
```
asadmin start-domain

```

```
asadmin start-datebase
```
最后进入到glassfish管理后台将打包好的.war文件部署到glassfish

