####[github项目地址： https://github.com/jcalaz/tip](https://github.com/jcalaz/tip)

> tip整合了自己学习编程的资源，包括代码小实现，博客，开源项目收藏，算法，设计模式等等，会不定时更新

### JAVAEE

- ####权限引擎
  1. [Apache Shiro:是一个强大且易用的Java安全框架,执行身份验证、授权、密码学和会话管理](http://shiro.apache.org/get-started.html)
  2. [Spring Security:是一个能够为基于Spring的企业应用系统提供声明式的安全访问控制解决方案的安全框架](http://projects.spring.io/spring-security/)
  3. [kisso = cookie sso 基于 Cookie 的 SSO 中间件，它是一把快速开发 java Web 登录系统（SSO）的瑞士军刀](http://git.oschina.net/baomidou/kisso)
  
- ####验证码
  1. [JCaptcha:是一个用来生成验证码的开源Java类库，目前最新的版本是2.0。](http://jcaptcha.sourceforge.net/)
  2. [patchca: 简单强大零依赖](https://github.com/pusuo/patchca)
  2. [kaptcha:是一个扩展自 simplecaptcha 的验证码库](https://github.com/axet/kaptcha)
  
- ####分布式框架
  1. [Spring Cloud: 分布式一站式解决，将各家公司开发的比较成熟、经得起实际考验的服务框架组合起来](http://projects.spring.io/spring-cloud/)
  2. [dubbo: 是一个分布式服务框架，致力于提供高性能和透明化的RPC远程服务调用方案，是阿里巴巴SOA服务化治理方案的核心框架](http://dubbo.io/)
  3. [dubbox:当当根据自身的需求，为Dubbo实现了一些新的功能，并将其命名为Dubbox](https://github.com/dangdangdotcom/dubbox)
  4. [finatra: twitter基于scala开发](https://github.com/twitter/finatra)
  5. [motan: 新浪轻量级RPC框架](https://github.com/weibocom/motan)
  6. [Thrift: facebook开源，支持多种语言](http://thrift.apache.org/)
  7. [grpc: 谷歌开源，支持跨语言](http://www.grpc.io/)
  
- ####模板引擎
   1. [freemarker: 老牌模板引擎，没用过](http://freemarker.org/docs/)
   2. [velocity: 老牌模板引擎，用过不错，就是不再更新了](http://velocity.apache.org/)
   3. [thymeleaf: 3.0出了，性能稍微差点，不过越来越快了，不跑服务器可以直接在浏览器显示，开发起来比较爽](http://www.thymeleaf.org/documentation.html)
   4. [beetl: 国产，性能高](http://ibeetl.com/)
   
- ####依赖注入
   1. [Spring IOC: 不用说了，注解后越来越爽了](http://projects.spring.io/spring-framework/)
   2. [google guice: 谷歌出品，更轻量级，速度更快，但是开发效率感觉不如spring ioc高，尤其现在到处spring全家桶](https://github.com/google/guice)
   
- ####ORM
   1. [Mybatis: 支持定制化 SQL、存储过程以及高级映射的优秀的持久层框架，需要手写sql，灵活，可控性强](http://www.mybatis.org/mybatis-3/zh/)
   2. [Spring data JPA: Hibernate二次封装，开发效率高，自动帮你完成很多东西](http://projects.spring.io/spring-data-jpa/)
   3. [Hibernate: 老牌强大ORM，用的不多，开发效率相比spring data jpa感觉差不少](http://hibernate.org/orm/)
   4. [JOOQ: DSL写法，有点类似动态语言了，感觉中小项目用起来会很爽](http://www.jooq.org/)
   5. [spring data mongo: 类似spring data jpa，开发效率高，复杂操作使用MongoTemplate](http://projects.spring.io/spring-data-mongodb/)
   
- ####日志
   1. [commons-logging: 日志接口，会自动装载具体的日志系统，采用ClassLoader寻找和载入底层的日志库，没有第三方会使用JDK自带](http://commons.apache.org/proper/commons-logging/)
   2. [slf4j: 日志接口，通过各种桥接包判断实现，在编译时静态绑定真正的日志库](http://www.slf4j.org/)
   3. [log4j: 日志实现，较早](http://logging.apache.org/log4j/1.2/)
   4. [logback: 日志实现，相比log4j，性能更好，功能更强大](http://logback.qos.ch/)
   5. [log4j2: 日志实现，配置更强大，支持插件化，使用Disruptor实现异步日志，性能最好](http://logging.apache.org/log4j/2.x/)
   
- ####搜索引擎
   1. [ElasticSearch: 基于Lucene RESTful web接口的搜索服务器。](https://www.elastic.co/guide/en/elasticsearch/reference/current/search-search.html)
   2. [Solr: 高性能，基于Lucene的全文搜索服务器](http://lucene.apache.org/solr/)
   3. [Lucene: 一个全文检索引擎的架构，提供了完整的查询引擎和索引引擎，部分文本分析引擎](https://lucene.apache.org/)
   4. [Nutch: 提供了我们运行自己的搜索引擎所需的全部工具,包括全文搜索和Web爬虫](http://nutch.apache.org/)
   
- ####爬虫
    1. [Heritrix: 最出色之处在于它良好的可扩展性，方便用户实现自己的抓取逻辑](https://webarchive.jira.com/wiki/display/Heritrix)
    2. [jsoup: 一款Java 的HTML解析器，可直接解析URL地址、HTML文本内容](https://jsoup.org/)
    3. [crawler4j: 提供了简单易用的接口，可以在几分钟内创建一个多线程网络爬虫](https://github.com/yasserg/crawler4j)
    4. [WebCollector: 一个无须配置、便于二次开发爬虫内核，它提供精简的的API，只需少量代码即可实现一个功能强大的爬虫](http://crawlscript.github.io/WebCollector/)
    5. [WebMagic: 国产，完全模块化的设计,支持多线程抓取，分布式抓取，并支持自动重试、自定义UA/cookie等功能](https://git.oschina.net/flashsword20/webmagic)
    
   
- ####数据校验
    1. [Hibernate Validator](http://hibernate.org/validator/)
    2. [Bean Validation: 基于Hibernate Validator](http://beanvalidation.org/)
    
- ####restful
    1. [spring mvc: 类加个@RestController或者方法加个@ResponseBody](https://spring.io/guides/gs/rest-service/)
    2. [jersey: 实现了JAX-RS规范](https://jersey.java.net/)
    3. [resteasy: JBoss项目，实现了JAX-RS规范，性能高 ](http://resteasy.jboss.org/)
    
- ####消息中间件
    1. [ActiveMQ: 完全支持JMS1.1和J2EE 1.4规范的消息队列](http://activemq.apache.org/)
    2. [RabbitMq:Erlang编写，在AMQP基础上完整的，可复用的企业消息系统](http://www.rabbitmq.com/)
    3. [kafka: scala编写的高吞吐量的分布式发布订阅消息系统，常用于日志](http://kafka.apache.org/)
    4. [RocketMQ: 阿里巴巴的MQ中间件,在其多个产品下使用，并能够撑住双十一的大流量](https://github.com/apache/incubator-rocketmq)

- ####响应式编程
    1. [reactor: spring社区开源，在spring 5.0直接引入](http://projectreactor.io/)
    2. [vert.x: 基于netty,可以通过它使用JavaScript、Ruby、Groovy、Java、甚至是混合语言来编写应用](http://vertx.io/)
    3. [RxJava: 安卓上用的特别多，特别与RxAndroid,Retrofit等结合使用](https://github.com/ReactiveX/RxJava)
    
- ####热加载
    1. [JRebel: 收费，idea，eclipse，netbeans都有它的插件](https://zeroturnaround.com/software/jrebel/)
    2. [spring-loaded: spring开源热更新工具](https://github.com/spring-projects/spring-loaded)
    
- ####数据库连接池
    1. [HikariCP: 性能最高的数据库连接池](http://brettwooldridge.github.io/HikariCP/)
    2. [druid: 阿里出品，为监控而生的数据库连接池](https://github.com/alibaba/druid)

- ####测试工具
    1. [Mockito: 允许使用自动化的单元测试创建和测试双对象，以达到测试驱动开发和行为驱动开发的目的](http://site.mockito.org/)
    2. [JUnit: 最常使用的单元测试工具](http://junit.org/junit4/)
    3. [TestNG: 主要功能是覆盖范围更广的测试分类，如单元、功能性、端到端，一体化等](http://testng.org/doc/index.html)
- ####开源博客
    1. [jcalaBlog: 基于spring boot的个人博客，本来写给自己用，写完后开源了，有时间重构](https://github.com/jcalaz/jcalaBlog)
    2. [Solo: 是一款一个命令就能搭建好的 Java 开源博客系统，并内置了 15+ 套精心制作的皮肤](https://github.com/b3log/solo)
  
- ####序列化
    1. [FlatBuffers: 相较于Protocol Buffers，其更适用于移动设备](https://github.com/google/flatbuffers)
    2. [protobuf: 高性能，跨语言，也是google出品](https://github.com/google/protobuf)
    3. [jprotobuf: 针对Java程序开发一套简易类库，目的是简化java语言对protobuf类库的使用](https://github.com/jhunters/jprotobuf)
    3. [FST: 重新实现的Java快速对象序列化的开发包,序列化速度更快、体积更小，而且兼容JDK原生的序列化](https://github.com/RuedigerMoeller/fast-serialization)
    4. [Kryo: 快速高效的Java序列化框架,支持论文件、数据库或网络数据，自动深拷贝、浅拷贝](https://github.com/EsotericSoftware/kryo)
    5. [MessagePack: 基于二进制高效的对象序列化类库,跨语言,比JSON更快速也更轻巧](https://github.com/msgpack/msgpack)
    6. [thrift: 跨语言，不仅仅包括序列化，是一个远程服务调用框架，facebook开源](http://thrift.apache.org/)
    
- ####其他
    1. [spring-retry: 操作失败后，优雅自动重新尝试](https://github.com/spring-projects/spring-retry)
    2. [Flyway : 是一个敏捷工具，用于数据库的移植](https://flywaydb.org/)
    
  
### JVM和字节码

- #### 字节码工具
  1. [ASM:  是一个 Java 字节码操控框架。它能够以二进制形式修改已有类或者动态生成类,性能高，但不如javassist简单](http://asm.ow2.org/)
  2. [Javassist: 是一个开源的分析、编辑和创建Java字节码的类库,无须了解JVM指令，java编码即可](http://jboss-javassist.github.io/javassist/)
  3. [jd-gui: java反编译](http://jd.benow.ca/)
  4. [jbe : java字节码修改工具](http://www.cs.ioc.ee/~ando/jbe/)
  
- ####JVM编程语言
  1. [groovy: 类似ruby的动态语言，gradle的编写语言](http://www.groovy-lang.org/)
  2. [scala: 强大的多范式编程语言，有spark，akka，kafka等开源项目](http://www.scala-lang.org/)
  3. [clojure: 动态Lisp方言](https://www.clojure.org/)
  4. [kotlin: jetbrains开发，目前多用于安卓开发，简化版的scala](http://kotlinlang.org/)
  5. [lux: 正在开发中的静态lisp方言](https://github.com/LuxLang/lux)
  
### 工具包
  1. [strman-java: 一个字符串处理工具,使用它可以解决几乎所有字符串处理场景](https://github.com/shekhargulati/strman-java)
  2. [jgit: java实现git操作](http://www.eclipse.org/jgit/)
  3. [Guava: Google开源，包含许多Google核心的Java常用库](https://github.com/google/guava)
  4. [apache commons: 包含了很多开源的工具](http://commons.apache.org/)
  5. [Lombok: 注解通过编译器生成getter,setter,builder等代码](https://projectlombok.org/)
  6. [Chronicle Map: 基于内存的键值对存储,低延迟、高并发,支持持久化到磁盘，以及多键值查询](https://github.com/OpenHFT/Chronicle-Map)
  
### 学习
  1. [99-Problems: 对三种不同的语言Java 8,Scala和Haskell分别提出了99个问题，让你通过使用特定语言编程来提供一个最优的解决方案](https://github.com/shekhargulati/99-problems/tree/master/java8)
  2. [java-design-patterns: java设计模式学习](https://github.com/iluwatar/java-design-patterns)