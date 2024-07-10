## 来源: reactor feign
## 修改: 修复reactor feign 在SpringCloudGateway中报错的问题，错误信息如下：
https://juejin.cn/post/7337513012394541095
## 版本信息: SpringBoot3.2，JDK17
## 使用: 下载到本地后，修改如下，源码主要是修改了 configuration 中的代码
    <dependency>
        <groupId>com.playtika.reactivefeign</groupId>
        <artifactId>feign-reactor-spring-configuration</artifactId>
        <version>4.0.3-SNAPSHOT</version>
    </dependency>