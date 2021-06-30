**项目说明** 
- renren-fast是一个轻量级的，前后端分离的Java快速开发平台，能快速开发项目并交付【接私活利器】
- 支持MySQL、Oracle、SQL Server、PostgreSQL等主流数据库
- 前端地址：https://gitee.com/renrenio/renren-fast-vue
- 代码生成器：https://gitee.com/renrenio/renren-generator

<br>
**部署文件修改**
本项目在renren-fast的官方项目中对如下文件进行了修改，以满足个人部署的需求：
- src/main/resources/application-dev.yml 更改数据库链接地址，并将driver更改为jdbc4
- src/main/resources/application.yml 更改了port及redis的连接方式
- pom.xml 更改mysql的版本为5.7.21及mysql-connector-java的版本为5.1.49

<br>

**编译方式**
```shell
mvn clean install -Dmaven.test.skip=true
```
