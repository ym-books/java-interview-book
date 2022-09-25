**1. @Component, @Controller, @Repository, @Service注解的区别**

@Component： 泛指组件，组件不好归类的时候用这个注解标注。

`@Controller, @Repository, @Service`
这三个注解其实是`@Component`的一个扩展，按`Spring MVC`结构定义特殊的注解，以便后面做一些特殊的处理。

@Controller: 用于标注控制层组件

@Service: 用于标注业务层组件

@Repository: 用于标注数据访问组件，即DAO层组件
