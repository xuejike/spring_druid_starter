# spring_druid_starter [![](https://jitpack.io/v/xuejike/spring_druid_starter.svg)](https://jitpack.io/#xuejike/spring_druid_starter)
Spring boot 的Druid 数据库连接池 starter
## Maven地址


```xml
    <repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
	
```
```xml
	    <dependency>
    	    <groupId>com.github.xuejike</groupId>
    	    <artifactId>spring_druid_starter</artifactId>
    	    <version>v0.1</version>
    	</dependency>
```

## 使用方法
```properties
#开启druid数据库连接池
bd.datasource.druid.enabled=true
#开启druid数据库连接池监控  默认监控地址 /druid
bd.datasource.druid.monitor-enable=true
```

## 配置说明
