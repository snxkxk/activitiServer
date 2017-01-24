# 简介

## Maven方式运行

> mvn clean jetty:run

在 **pom.xml** 中配置了 **h2** 数据库与 **mysql** 数据库，默认启用 **h2** 数据库配置方式，如果使用 **mysql** 请启用mysql的配置(使用下面的命令)。

> mvn clean jetty:run -Pmysql


