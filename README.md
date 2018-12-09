# JotmAtomikosTree
事务管理


<pre>
Jotm:
      JOTM（Java Open Transaction Manager）是由ObjectWeb协会开发的功能完整的且资源开
   放的独立的事务管理器。
      它提供了JAVA应用程序的事务支持，而且与JTA兼容，

      JOTM特性：
              1）完全分布式事务支持，如果数据层，业务层，表示层运行在不同的JVM上，则有可能
                 有一个全程的事务跨越这些JVM，事务的内容在RMI/JRMP和RMI/IIOP上传播。
              2）整合JDBC，使用的XAPool例子就是一个XA兼容的JDBC连接池，可以预数据库相互
                 操作。XAPool类似于Jakarta DBCP，只是增加了XA兼容的特征
              3) 整合JMS
              5) WEB服务事项。
</pre>