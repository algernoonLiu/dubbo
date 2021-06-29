dubbo-container容器模块：是一个Standlone的容器，以简单的Main加载Spring启动，
因为服务通常不需要Tomcat/Jboss等Web容器的特性，没必要用Web容器去加载服务。

- dubbo-container-api：定义了org.apache.dubbo.container.Container接口，并提供加载所有容器启动的Main类。
- dubbo-container-spring提供了org.apache.dubbo.container.spring.SpringContainer。
- dubbo-container-log4j提供了org.apache.dubbo.container.log4j.Log4jContainer。
- dubbo-container-logback提供了org.apache.dubbo.container.logback.LogbackContainer。