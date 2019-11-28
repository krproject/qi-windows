# qi-windows

器（qi），工欲善其事，必先利其器！  

本工程包含了在Windows上进行krproject开发所需的工具及软件依赖，方便以命令行的方式一键安装！

# 安装使用

1. 安装Scoop  

   参考：https://scoop.sh

2. 添加Bucket

```cmd
scoop bucket add krproject https://github.com/krproject/qi-windows
```

3. 安装工具软件

```cmd
scoop install krproject/typora
scoop install krproject/sts
scoop install krproject/vscode
...

```

4. 配置工具软件

   。。。


# 工具列表

|工具名称|工具描述|功能分类|安装命令|
|-|-|-|-|
|[git](https://git-scm.com/)|分布式版本管理|版本管理|`scoop install git`|
|[Node](https://nodejs.org)|前端node语言|编程语言|`scoop install krproject/nodejs-lts`|
|[Java](https://www.java.com)|后端java语言|编程语言|`scoop install krproject/oraclejdk8u`|
|[Maven](https://maven.apache.org/)|java依赖与编译管理|编程语言|`scoop install krproject/maven`|
|[VSCode](https://code.visualstudio.com/)|前端开发编辑器|编辑器|`scoop install krproject/vscode`|
|[STS](https://spring.io/tools)|后端开发编辑器|编辑器|`scoop install krproject/sts`|
|[DbVisualizer](https://www.dbvis.com/)|数据库管理与分析|开发工具|`scoop install krproject/dbvis`|
|[Xshell Plus](https://www.netsarang.com)|ssh及ftp站点管理|开发工具|-|
|[Docker Desktop](https://www.docker.com/)|镜像管理|开发工具|-|
|[VirtualBox](https://www.virtualbox.org/)|虚拟机管理|开发工具|-|
|[Postman](https://www.getpostman.com/)|接口测试工具|测试工具|`scoop install krproject/postman`|
|[JMeter](https://jmeter.apache.org/)|压力测试工具|测试工具|`scoop install krproject/jmeter`|
|[Foxmail](https://www.foxmail.com/)|邮件通讯|沟通工具|-|
|[WPS](http://www.wps.cn/)|文档编辑、流程图、思维导图|设计工具|-|
|[Axure RP](https://www.axure.com/)|原型设计|设计工具|-|

