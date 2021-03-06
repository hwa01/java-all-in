
<h2>《Java的世界》</h2>

* [Spring]
  * [动态代理](https://github.com/hwa01/java-all-in/blob/master/README.md#动态代理)
  * [JDK动态代理](https://github.com/hwa01/java-all-in/blob/master/README.md#JDK动态代理)
  * [Cglib动态代理](https://blog.csdn.net/sunnycoco05/article/details/78853148)
  * [Spring动态代理](https://blog.csdn.net/sunnycoco05/article/details/78901449)
  * [Java查看动态代理生成的代码](https://www.cnblogs.com/ctgulong/p/5011614.html)
  * [JDK动态代理生成.class文件和cglib动态代理生成.class文件](https://blog.csdn.net/zhao1991abc/article/details/52926620)

# 动态代理

## JDK动态代理
* [《JDK动态代理实现原理》](http://rejoy.iteye.com/blog/1627405)
> 打印出proxy
* [《JDK Proxy 解析基于Java 8》](https://blog.csdn.net/sunnycoco05/article/details/78845878)
> 打印出proxy
	
	
## spring中的单例，及单例模式
* [由Spring框架中的单例模式想到的](http://www.cnblogs.com/chengxuyuanzhilu/p/6404991.html)
* [Spring Bean单例与线程安全](https://www.cnblogs.com/redcool/p/6398760.html)


## @Transactional
* [@Transactional的使用及原理](https://blog.csdn.net/aichuanwendang/article/details/53306351)
* [@Transactional是如何工作的](https://mp.weixin.qq.com/s/ZwhkUQF1Nun9pNrFI-3a6w)
> 介绍了spring AopProxy的两种方式，以及@transactional常见使用错误的原因

## 同一个类中的注解方法互相调用时,注解机制可能是无效的
* [在同一个类中调用另一个方法没有触发 Spring AOP 的问题](https://segmentfault.com/a/1190000008379179)
> 可以用自己注入自己的方式来实现
* [同类中嵌套AOP--注解事物在同一类中嵌套调用不生效](https://www.cnblogs.com/vi-2525/p/8761544.html)
* [Spring同一个类中注解方法互相调用的问题](https://www.cnblogs.com/shuzl/p/5304762.html)
* [在同一个类中，一个方法调用另外一个有注解的方法，注解失效的原因和解决方法](https://blog.csdn.net/wudiyong22/article/details/77853347)

# [todo] 
*  为什么Spring的@Autowire用的是cglib？
