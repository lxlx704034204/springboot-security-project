﻿## springboot-security-project
**基于`springboot2` + `springsecurity` + `mybatis` + `redis` + `swagger` + `oauth2` 的脚手架工程(前后端分离)**
1. 内含freemarker的代码生成器，可以一键根据表名直接生成controller、service、dao、mapper等基础代码，
大大提高了开发效率，让你更专注于对业务的开发。
2. springsecurity目前使用的是基于权限的动态校验，新增权限后不需要重启项目，重新登录即可。
3. 框架内已包含许多工具类，MD5加密、json、POI的excel文档操作，以及时间和日期等常见工具类。
4. 采用了@Log对项目日志的记录。
5. 加入对OAuth2的支持 （[博客地址](https://blog.csdn.net/qq_34997906/article/details/89600076)）