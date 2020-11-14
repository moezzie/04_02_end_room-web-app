# 04_02_end_room-web-app

```
/home/moezzie/.jdks/openjdk-15.0.1/bin/java -XX:TieredStopAtLevel=1 -noverify -Dspring.output.ansi.enabled=always -Dcom.sun.management.jmxremote -Dspring.jmx.enabled=true -Dspring.liveBeansView.mbeanDomain -Dspring.application.admin.enabled=true -javaagent:/snap/intellij-idea-ultimate/253/lib/idea_rt.jar=34489:/snap/intellij-idea-ultimate/253/bin -Dfile.encoding=UTF-8 -classpath /home/moezzie/Downloads/Ex_Files_SpringBoot2_EssT(1)/Ex_Files_SpringBoot2_EssT/Exercise Files/Chapter 4/04_02/04_02_End/room-web-app/target/classes:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter-thymeleaf/2.0.4.RELEASE/spring-boot-starter-thymeleaf-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter/2.0.4.RELEASE/spring-boot-starter-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter-logging/2.0.4.RELEASE/spring-boot-starter-logging-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/ch/qos/logback/logback-classic/1.2.3/logback-classic-1.2.3.jar:/home/moezzie/.m2/repository/ch/qos/logback/logback-core/1.2.3/logback-core-1.2.3.jar:/home/moezzie/.m2/repository/org/apache/logging/log4j/log4j-to-slf4j/2.10.0/log4j-to-slf4j-2.10.0.jar:/home/moezzie/.m2/repository/org/apache/logging/log4j/log4j-api/2.10.0/log4j-api-2.10.0.jar:/home/moezzie/.m2/repository/org/slf4j/jul-to-slf4j/1.7.25/jul-to-slf4j-1.7.25.jar:/home/moezzie/.m2/repository/javax/annotation/javax.annotation-api/1.3.2/javax.annotation-api-1.3.2.jar:/home/moezzie/.m2/repository/org/yaml/snakeyaml/1.19/snakeyaml-1.19.jar:/home/moezzie/.m2/repository/org/thymeleaf/thymeleaf-spring5/3.0.9.RELEASE/thymeleaf-spring5-3.0.9.RELEASE.jar:/home/moezzie/.m2/repository/org/thymeleaf/thymeleaf/3.0.9.RELEASE/thymeleaf-3.0.9.RELEASE.jar:/home/moezzie/.m2/repository/org/attoparser/attoparser/2.0.4.RELEASE/attoparser-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/unbescape/unbescape/1.1.5.RELEASE/unbescape-1.1.5.RELEASE.jar:/home/moezzie/.m2/repository/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar:/home/moezzie/.m2/repository/org/thymeleaf/extras/thymeleaf-extras-java8time/3.0.1.RELEASE/thymeleaf-extras-java8time-3.0.1.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter-web/2.0.4.RELEASE/spring-boot-starter-web-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter-json/2.0.4.RELEASE/spring-boot-starter-json-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/com/fasterxml/jackson/datatype/jackson-datatype-jdk8/2.9.6/jackson-datatype-jdk8-2.9.6.jar:/home/moezzie/.m2/repository/com/fasterxml/jackson/datatype/jackson-datatype-jsr310/2.9.6/jackson-datatype-jsr310-2.9.6.jar:/home/moezzie/.m2/repository/com/fasterxml/jackson/module/jackson-module-parameter-names/2.9.6/jackson-module-parameter-names-2.9.6.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter-tomcat/2.0.4.RELEASE/spring-boot-starter-tomcat-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/apache/tomcat/embed/tomcat-embed-core/8.5.32/tomcat-embed-core-8.5.32.jar:/home/moezzie/.m2/repository/org/apache/tomcat/embed/tomcat-embed-el/8.5.32/tomcat-embed-el-8.5.32.jar:/home/moezzie/.m2/repository/org/apache/tomcat/embed/tomcat-embed-websocket/8.5.32/tomcat-embed-websocket-8.5.32.jar:/home/moezzie/.m2/repository/org/hibernate/validator/hibernate-validator/6.0.11.Final/hibernate-validator-6.0.11.Final.jar:/home/moezzie/.m2/repository/javax/validation/validation-api/2.0.1.Final/validation-api-2.0.1.Final.jar:/home/moezzie/.m2/repository/org/jboss/logging/jboss-logging/3.3.2.Final/jboss-logging-3.3.2.Final.jar:/home/moezzie/.m2/repository/com/fasterxml/classmate/1.3.4/classmate-1.3.4.jar:/home/moezzie/.m2/repository/org/openjfx/javafx.base/11.0.0-SNAPSHOT/javafx.base-11.0.0-20180702.224858-3.jar:/home/moezzie/.m2/repository/org/openjfx/javafx.base/11.0.0-SNAPSHOT/javafx.base-11.0.0-20180702.223831-2-linux.jar:/home/moezzie/.m2/repository/org/openjfx/javafx.base/11.0.0-SNAPSHOT/javafx.base-11.0.0-20180702.224858-3-mac.jar:/home/moezzie/.m2/repository/org/openjfx/javafx.base/11.0.0-SNAPSHOT/javafx.base-11.0.0-20180629.175051-1-win.jar:/home/moezzie/.m2/repository/org/springframework/spring-web/5.0.8.RELEASE/spring-web-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-beans/5.0.8.RELEASE/spring-beans-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-webmvc/5.0.8.RELEASE/spring-webmvc-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-aop/5.0.8.RELEASE/spring-aop-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-context/5.0.8.RELEASE/spring-context-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-expression/5.0.8.RELEASE/spring-expression-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/com/fasterxml/jackson/dataformat/jackson-dataformat-xml/2.9.6/jackson-dataformat-xml-2.9.6.jar:/home/moezzie/.m2/repository/com/fasterxml/jackson/core/jackson-core/2.9.6/jackson-core-2.9.6.jar:/home/moezzie/.m2/repository/com/fasterxml/jackson/core/jackson-annotations/2.9.0/jackson-annotations-2.9.0.jar:/home/moezzie/.m2/repository/com/fasterxml/jackson/core/jackson-databind/2.9.6/jackson-databind-2.9.6.jar:/home/moezzie/.m2/repository/com/fasterxml/jackson/module/jackson-module-jaxb-annotations/2.9.6/jackson-module-jaxb-annotations-2.9.6.jar:/home/moezzie/.m2/repository/org/codehaus/woodstox/stax2-api/3.1.4/stax2-api-3.1.4.jar:/home/moezzie/.m2/repository/com/fasterxml/woodstox/woodstox-core/5.0.3/woodstox-core-5.0.3.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-devtools/2.0.4.RELEASE/spring-boot-devtools-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot/2.0.4.RELEASE/spring-boot-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-autoconfigure/2.0.4.RELEASE/spring-boot-autoconfigure-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter-data-jpa/2.0.4.RELEASE/spring-boot-starter-data-jpa-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter-aop/2.0.4.RELEASE/spring-boot-starter-aop-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/org/aspectj/aspectjweaver/1.8.13/aspectjweaver-1.8.13.jar:/home/moezzie/.m2/repository/org/springframework/boot/spring-boot-starter-jdbc/2.0.4.RELEASE/spring-boot-starter-jdbc-2.0.4.RELEASE.jar:/home/moezzie/.m2/repository/com/zaxxer/HikariCP/2.7.9/HikariCP-2.7.9.jar:/home/moezzie/.m2/repository/org/springframework/spring-jdbc/5.0.8.RELEASE/spring-jdbc-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/hibernate/hibernate-core/5.2.17.Final/hibernate-core-5.2.17.Final.jar:/home/moezzie/.m2/repository/org/hibernate/javax/persistence/hibernate-jpa-2.1-api/1.0.2.Final/hibernate-jpa-2.1-api-1.0.2.Final.jar:/home/moezzie/.m2/repository/org/javassist/javassist/3.22.0-GA/javassist-3.22.0-GA.jar:/home/moezzie/.m2/repository/antlr/antlr/2.7.7/antlr-2.7.7.jar:/home/moezzie/.m2/repository/org/jboss/jandex/2.0.3.Final/jandex-2.0.3.Final.jar:/home/moezzie/.m2/repository/dom4j/dom4j/1.6.1/dom4j-1.6.1.jar:/home/moezzie/.m2/repository/org/hibernate/common/hibernate-commons-annotations/5.0.1.Final/hibernate-commons-annotations-5.0.1.Final.jar:/home/moezzie/.m2/repository/javax/transaction/javax.transaction-api/1.2/javax.transaction-api-1.2.jar:/home/moezzie/.m2/repository/org/springframework/data/spring-data-jpa/2.0.9.RELEASE/spring-data-jpa-2.0.9.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/data/spring-data-commons/2.0.9.RELEASE/spring-data-commons-2.0.9.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-orm/5.0.8.RELEASE/spring-orm-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-tx/5.0.8.RELEASE/spring-tx-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-aspects/5.0.8.RELEASE/spring-aspects-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/com/h2database/h2/1.4.197/h2-1.4.197.jar:/home/moezzie/.m2/repository/org/springframework/spring-core/5.0.8.RELEASE/spring-core-5.0.8.RELEASE.jar:/home/moezzie/.m2/repository/org/springframework/spring-jcl/5.0.8.RELEASE/spring-jcl-5.0.8.RELEASE.jar com.frankmoley.boot.landon.roomwebapp.RoomWebAppApplication
OpenJDK 64-Bit Server VM warning: Options -Xverify:none and -noverify were deprecated in JDK 13 and will likely be removed in a future release.
00:18:12.863 [main] DEBUG org.springframework.boot.devtools.settings.DevToolsSettings - Included patterns for restart : []
00:18:12.865 [main] DEBUG org.springframework.boot.devtools.settings.DevToolsSettings - Excluded patterns for restart : [/spring-boot-starter-[\w-]+/, /spring-boot/target/classes/, /spring-boot-starter/target/classes/, /spring-boot-devtools/target/classes/, /spring-boot-actuator/target/classes/, /spring-boot-autoconfigure/target/classes/]
00:18:12.865 [main] DEBUG org.springframework.boot.devtools.restart.ChangeableUrls - Matching URLs for reloading : [file:/home/moezzie/Downloads/Ex_Files_SpringBoot2_EssT(1)/Ex_Files_SpringBoot2_EssT/Exercise%20Files/Chapter%204/04_02/04_02_End/room-web-app/target/classes/]

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v2.0.4.RELEASE)

2020-11-15 00:18:12.983  INFO 7537 --- [  restartedMain] c.f.b.l.r.RoomWebAppApplication          : Starting RoomWebAppApplication on moezzies-desktop with PID 7537 (started by moezzie in /home/moezzie/Downloads/Ex_Files_SpringBoot2_EssT(1)/Ex_Files_SpringBoot2_EssT/Exercise Files/Chapter 4/04_02/04_02_End/room-web-app)
2020-11-15 00:18:12.983  INFO 7537 --- [  restartedMain] c.f.b.l.r.RoomWebAppApplication          : No active profile set, falling back to default profiles: default
2020-11-15 00:18:13.006  INFO 7537 --- [  restartedMain] ConfigServletWebServerApplicationContext : Refreshing org.springframework.boot.web.servlet.context.AnnotationConfigServletWebServerApplicationContext@4434377a: startup date [Sun Nov 15 00:18:13 CET 2020]; root of context hierarchy
WARNING: An illegal reflective access operation has occurred
WARNING: Illegal reflective access by org.springframework.cglib.core.ReflectUtils$1 (file:/home/moezzie/.m2/repository/org/springframework/spring-core/5.0.8.RELEASE/spring-core-5.0.8.RELEASE.jar) to method java.lang.ClassLoader.defineClass(java.lang.String,byte[],int,int,java.security.ProtectionDomain)
WARNING: Please consider reporting this to the maintainers of org.springframework.cglib.core.ReflectUtils$1
WARNING: Use --illegal-access=warn to enable warnings of further illegal reflective access operations
WARNING: All illegal access operations will be denied in a future release
2020-11-15 00:18:13.552  INFO 7537 --- [  restartedMain] trationDelegate$BeanPostProcessorChecker : Bean 'org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration' of type [org.springframework.transaction.annotation.ProxyTransactionManagementConfiguration$$EnhancerBySpringCGLIB$$4ea6e235] is not eligible for getting processed by all BeanPostProcessors (for example: not eligible for auto-proxying)
2020-11-15 00:18:13.757  INFO 7537 --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2020-11-15 00:18:13.767  INFO 7537 --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2020-11-15 00:18:13.767  INFO 7537 --- [  restartedMain] org.apache.catalina.core.StandardEngine  : Starting Servlet Engine: Apache Tomcat/8.5.32
2020-11-15 00:18:13.770  INFO 7537 --- [ost-startStop-1] o.a.catalina.core.AprLifecycleListener   : The APR based Apache Tomcat Native library which allows optimal performance in production environments was not found on the java.library.path: [/usr/java/packages/lib:/usr/lib64:/lib64:/lib:/usr/lib]
2020-11-15 00:18:13.816  INFO 7537 --- [ost-startStop-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2020-11-15 00:18:13.816  INFO 7537 --- [ost-startStop-1] o.s.web.context.ContextLoader            : Root WebApplicationContext: initialization completed in 814 ms
2020-11-15 00:18:13.847  INFO 7537 --- [ost-startStop-1] o.s.b.w.servlet.ServletRegistrationBean  : Servlet dispatcherServlet mapped to [/]
2020-11-15 00:18:13.847  INFO 7537 --- [ost-startStop-1] o.s.b.w.servlet.ServletRegistrationBean  : Servlet webServlet mapped to [/h2-console/*]
2020-11-15 00:18:13.849  INFO 7537 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'characterEncodingFilter' to: [/*]
2020-11-15 00:18:13.849  INFO 7537 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'hiddenHttpMethodFilter' to: [/*]
2020-11-15 00:18:13.849  INFO 7537 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'httpPutFormContentFilter' to: [/*]
2020-11-15 00:18:13.849  INFO 7537 --- [ost-startStop-1] o.s.b.w.servlet.FilterRegistrationBean   : Mapping filter: 'requestContextFilter' to: [/*]
2020-11-15 00:18:13.884  INFO 7537 --- [  restartedMain] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2020-11-15 00:18:13.922  INFO 7537 --- [  restartedMain] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2020-11-15 00:18:13.928  INFO 7537 --- [  restartedMain] o.s.jdbc.datasource.init.ScriptUtils     : Executing SQL script from URL [file:/home/moezzie/Downloads/Ex_Files_SpringBoot2_EssT(1)/Ex_Files_SpringBoot2_EssT/Exercise%20Files/Chapter%204/04_02/04_02_End/room-web-app/target/classes/schema.sql]
2020-11-15 00:18:13.935  INFO 7537 --- [  restartedMain] o.s.jdbc.datasource.init.ScriptUtils     : Executed SQL script from URL [file:/home/moezzie/Downloads/Ex_Files_SpringBoot2_EssT(1)/Ex_Files_SpringBoot2_EssT/Exercise%20Files/Chapter%204/04_02/04_02_End/room-web-app/target/classes/schema.sql] in 7 ms.
2020-11-15 00:18:13.937  INFO 7537 --- [  restartedMain] o.s.jdbc.datasource.init.ScriptUtils     : Executing SQL script from URL [file:/home/moezzie/Downloads/Ex_Files_SpringBoot2_EssT(1)/Ex_Files_SpringBoot2_EssT/Exercise%20Files/Chapter%204/04_02/04_02_End/room-web-app/target/classes/data.sql]
2020-11-15 00:18:13.945  INFO 7537 --- [  restartedMain] o.s.jdbc.datasource.init.ScriptUtils     : Executed SQL script from URL [file:/home/moezzie/Downloads/Ex_Files_SpringBoot2_EssT(1)/Ex_Files_SpringBoot2_EssT/Exercise%20Files/Chapter%204/04_02/04_02_End/room-web-app/target/classes/data.sql] in 8 ms.
2020-11-15 00:18:13.988  INFO 7537 --- [  restartedMain] j.LocalContainerEntityManagerFactoryBean : Building JPA container EntityManagerFactory for persistence unit 'default'
2020-11-15 00:18:13.993  INFO 7537 --- [  restartedMain] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [
	name: default
	...]
2020-11-15 00:18:14.017  INFO 7537 --- [  restartedMain] org.hibernate.Version                    : HHH000412: Hibernate Core {5.2.17.Final}
2020-11-15 00:18:14.018  INFO 7537 --- [  restartedMain] org.hibernate.cfg.Environment            : HHH000206: hibernate.properties not found
2020-11-15 00:18:14.029  INFO 7537 --- [  restartedMain] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.0.1.Final}
2020-11-15 00:18:14.067  INFO 7537 --- [  restartedMain] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2020-11-15 00:18:14.193  WARN 7537 --- [  restartedMain] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: Invocation of init method failed; nested exception is javax.persistence.PersistenceException: [PersistenceUnit: default] Unable to build Hibernate SessionFactory; nested exception is org.hibernate.MappingException: Could not get constructor for org.hibernate.persister.entity.SingleTableEntityPersister
2020-11-15 00:18:14.194  WARN 7537 --- [  restartedMain] o.s.b.f.support.DisposableBeanAdapter    : Invocation of destroy method failed on bean with name 'inMemoryDatabaseShutdownExecutor': org.h2.jdbc.JdbcSQLException: Database is already closed (to disable automatic closing at VM shutdown, add ";DB_CLOSE_ON_EXIT=FALSE" to the db URL) [90121-197]
2020-11-15 00:18:14.194  INFO 7537 --- [  restartedMain] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown initiated...
2020-11-15 00:18:14.196  INFO 7537 --- [  restartedMain] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Shutdown completed.
2020-11-15 00:18:14.197  INFO 7537 --- [  restartedMain] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2020-11-15 00:18:14.207  INFO 7537 --- [  restartedMain] ConditionEvaluationReportLoggingListener : 

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
2020-11-15 00:18:14.212 ERROR 7537 --- [  restartedMain] o.s.boot.SpringApplication               : Application run failed

org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'entityManagerFactory' defined in class path resource [org/springframework/boot/autoconfigure/orm/jpa/HibernateJpaConfiguration.class]: Invocation of init method failed; nested exception is javax.persistence.PersistenceException: [PersistenceUnit: default] Unable to build Hibernate SessionFactory; nested exception is org.hibernate.MappingException: Could not get constructor for org.hibernate.persister.entity.SingleTableEntityPersister
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1699) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:573) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:495) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:317) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:222) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:315) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:199) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.context.support.AbstractApplicationContext.getBean(AbstractApplicationContext.java:1089) ~[spring-context-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:859) ~[spring-context-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:550) ~[spring-context-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:140) ~[spring-boot-2.0.4.RELEASE.jar:2.0.4.RELEASE]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:762) ~[spring-boot-2.0.4.RELEASE.jar:2.0.4.RELEASE]
	at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:398) ~[spring-boot-2.0.4.RELEASE.jar:2.0.4.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:330) ~[spring-boot-2.0.4.RELEASE.jar:2.0.4.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1258) ~[spring-boot-2.0.4.RELEASE.jar:2.0.4.RELEASE]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1246) ~[spring-boot-2.0.4.RELEASE.jar:2.0.4.RELEASE]
	at com.frankmoley.boot.landon.roomwebapp.RoomWebAppApplication.main(RoomWebAppApplication.java:10) ~[classes/:na]
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[na:na]
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:64) ~[na:na]
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[na:na]
	at java.base/java.lang.reflect.Method.invoke(Method.java:564) ~[na:na]
	at org.springframework.boot.devtools.restart.RestartLauncher.run(RestartLauncher.java:49) ~[spring-boot-devtools-2.0.4.RELEASE.jar:2.0.4.RELEASE]
Caused by: javax.persistence.PersistenceException: [PersistenceUnit: default] Unable to build Hibernate SessionFactory; nested exception is org.hibernate.MappingException: Could not get constructor for org.hibernate.persister.entity.SingleTableEntityPersister
	at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.buildNativeEntityManagerFactory(AbstractEntityManagerFactoryBean.java:402) ~[spring-orm-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.afterPropertiesSet(AbstractEntityManagerFactoryBean.java:377) ~[spring-orm-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.afterPropertiesSet(LocalContainerEntityManagerFactoryBean.java:341) ~[spring-orm-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.invokeInitMethods(AbstractAutowireCapableBeanFactory.java:1758) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.initializeBean(AbstractAutowireCapableBeanFactory.java:1695) ~[spring-beans-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	... 21 common frames omitted
Caused by: org.hibernate.MappingException: Could not get constructor for org.hibernate.persister.entity.SingleTableEntityPersister
	at org.hibernate.persister.internal.PersisterFactoryImpl.createEntityPersister(PersisterFactoryImpl.java:123) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.persister.internal.PersisterFactoryImpl.createEntityPersister(PersisterFactoryImpl.java:77) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.metamodel.internal.MetamodelImpl.initialize(MetamodelImpl.java:129) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.internal.SessionFactoryImpl.<init>(SessionFactoryImpl.java:300) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.boot.internal.SessionFactoryBuilderImpl.build(SessionFactoryBuilderImpl.java:462) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.jpa.boot.internal.EntityManagerFactoryBuilderImpl.build(EntityManagerFactoryBuilderImpl.java:892) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.springframework.orm.jpa.vendor.SpringHibernateJpaPersistenceProvider.createContainerEntityManagerFactory(SpringHibernateJpaPersistenceProvider.java:57) ~[spring-orm-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.orm.jpa.LocalContainerEntityManagerFactoryBean.createNativeEntityManagerFactory(LocalContainerEntityManagerFactoryBean.java:365) ~[spring-orm-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	at org.springframework.orm.jpa.AbstractEntityManagerFactoryBean.buildNativeEntityManagerFactory(AbstractEntityManagerFactoryBean.java:390) ~[spring-orm-5.0.8.RELEASE.jar:5.0.8.RELEASE]
	... 25 common frames omitted
Caused by: org.hibernate.HibernateException: Unable to instantiate default tuplizer [org.hibernate.tuple.entity.PojoEntityTuplizer]
	at org.hibernate.tuple.entity.EntityTuplizerFactory.constructTuplizer(EntityTuplizerFactory.java:91) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.tuple.entity.EntityTuplizerFactory.constructDefaultTuplizer(EntityTuplizerFactory.java:116) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.tuple.entity.EntityMetamodel.<init>(EntityMetamodel.java:382) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.persister.entity.AbstractEntityPersister.<init>(AbstractEntityPersister.java:519) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.persister.entity.SingleTableEntityPersister.<init>(SingleTableEntityPersister.java:124) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method) ~[na:na]
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:64) ~[na:na]
	at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45) ~[na:na]
	at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500) ~[na:na]
	at java.base/java.lang.reflect.Constructor.newInstance(Constructor.java:481) ~[na:na]
	at org.hibernate.persister.internal.PersisterFactoryImpl.createEntityPersister(PersisterFactoryImpl.java:96) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	... 33 common frames omitted
Caused by: java.lang.reflect.InvocationTargetException: null
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method) ~[na:na]
	at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:64) ~[na:na]
	at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45) ~[na:na]
	at java.base/java.lang.reflect.Constructor.newInstanceWithCaller(Constructor.java:500) ~[na:na]
	at java.base/java.lang.reflect.Constructor.newInstance(Constructor.java:481) ~[na:na]
	at org.hibernate.tuple.entity.EntityTuplizerFactory.constructTuplizer(EntityTuplizerFactory.java:88) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	... 43 common frames omitted
Caused by: java.lang.NullPointerException: Cannot invoke "java.lang.reflect.AccessibleObject.setAccessible(boolean)" because "ao" is null
	at javassist.util.proxy.SecurityActions.setAccessible(SecurityActions.java:103) ~[javassist-3.22.0-GA.jar:na]
	at javassist.util.proxy.DefineClassHelper.toClass3(DefineClassHelper.java:151) ~[javassist-3.22.0-GA.jar:na]
	at javassist.util.proxy.DefineClassHelper.toClass2(DefineClassHelper.java:134) ~[javassist-3.22.0-GA.jar:na]
	at javassist.util.proxy.DefineClassHelper.toClass(DefineClassHelper.java:95) ~[javassist-3.22.0-GA.jar:na]
	at javassist.util.proxy.FactoryHelper.toClass(FactoryHelper.java:131) ~[javassist-3.22.0-GA.jar:na]
	at javassist.util.proxy.ProxyFactory.createClass3(ProxyFactory.java:530) ~[javassist-3.22.0-GA.jar:na]
	at javassist.util.proxy.ProxyFactory.createClass2(ProxyFactory.java:515) ~[javassist-3.22.0-GA.jar:na]
	at javassist.util.proxy.ProxyFactory.createClass1(ProxyFactory.java:451) ~[javassist-3.22.0-GA.jar:na]
	at javassist.util.proxy.ProxyFactory.createClass(ProxyFactory.java:422) ~[javassist-3.22.0-GA.jar:na]
	at org.hibernate.proxy.pojo.javassist.JavassistProxyFactory.postInstantiate(JavassistProxyFactory.java:75) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.tuple.entity.PojoEntityTuplizer.buildProxyFactory(PojoEntityTuplizer.java:162) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.tuple.entity.AbstractEntityTuplizer.<init>(AbstractEntityTuplizer.java:156) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	at org.hibernate.tuple.entity.PojoEntityTuplizer.<init>(PojoEntityTuplizer.java:58) ~[hibernate-core-5.2.17.Final.jar:5.2.17.Final]
	... 49 common frames omitted


Process finished with exit code 0

```
