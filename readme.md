## parent说明

1.简介

```
 用于所有系统引入一个父类parent依赖
```

2.作用

```
 1. 定义JAVA编译编码
 2. 使用UTF-8格式编码
 3. 继承spring-boot-dependencies,这里定义了依赖的版本
 4. 定义与控制其他jar版本
 5. 执行打包操作配置
 6. 跳过自动测试配置
 7. 其他
```

3.用法

所有的工程都需要依赖的父POM.例如：

```xml
	<parent>
	   <groupId>com.aijava</groupId>
	   <artifactId>parent</artifactId>
	   <version>1.0.0-SNAPSHOT</version>
	</parent>
```

4.注意事项

```
1. 这里的大版本号一般不随便改
2. 这里的依赖版本升级需要经过全系统测试
3. 需要制定版本升级规范
```

