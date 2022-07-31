#### 01. What component is part of the data access layer in the Spring Framework?
* Aspects
* JMS
* Beans
* Core
* Web
* Servelet
* Expression language
```
Answer
 B
 ```
 Explantion - Java applications that use Java Message Service (JMS) are called JMS clients. A JMS client can create, send, receive, and read messages. The clients who send messages are called producers and those who receive messages are called consumers.
 
#### 02. How to use “idref” in the spring framework?
* With setter method
* With getter method
* With setter method and constructor argument
* With getter method and constructor argument

```
Answer
 C
 ```
 
 Explantion - In the Spring framework, idref consists of transmitting the identifier of a bean to another bean. Example: <idref bean="PointA">. idrefs can be considered of type Strings.
 When using “idref”, the parameters of the Setter method or the constructor that we define/inject must be of type Strings.
 
 #### 03. Which class does the IoC container represent?
* ApplicationContext
* ServletContext
* RootContext
* WebApplicationContext

```
Answer
 A
 ```
 
Explantion - The IoC (Inversion of Control) container is responsible for instantiating, configuring, and aggregating objects. The IoC container obtains information from the XML file and operates accordingly. The main tasks performed by the IoC container are as follows:
Instantiate the application class
Configure the object
Aggregate dependencies between objects

#### 04. In which version of spring has Spring Expression Language been supported?
* Spring 1.0
* Spring 2.0
* Spring 2.5
* Spring 3.0

```
Answer
 D
 ```
 
Explantion - Spring 3.0 introduces Spring Expression Language (SpEL), a powerful expression language that supports querying and manipulating object graph at runtime. 
With SpEL, Spring applications can overcome the limitation of using only fixed values in configuration files. 
It can be used for bean definitions in XML-based and annotation-based configurations.

#### 05. In which version of spring have the features of Java 5 been introduced?
* Spring 1.0
* Spring 2.0
* Spring 2.5
* Spring 3.0

```
Answer
 D
 ```
 
Explantion - The main API of the Spring 3.0 framework uses Java 5; therefore, Java5 or later is required to run Spring 3.0 applications. 
Java 5 features, such as generic types, annotations, etc, can be used in Spring 3.0 framework applications. 
Spring 3.0 is fully compatible with JEE1.4 and JEE5 models.

#### 06. How to get the DAO object in the spring framework?
* Use the “new” keyword
* Using Spring Dependency Injection
* Both A and B are true.
* None of the above

```
Answer
 B
 ```
 
Explantion - If a class A expects a data access object (DAO) to receive data from a database, you can easily create another test object(mock) for a database connection and inject that object into A to test A without having a database connection. 
Dependency injection based design is possible with the Java standard. 
Spring simply simplifies the use of dependency injection by providing a standard way to provide the configuration and by managing the references of the created objects.

#### 07. Which of the following statements is true?
* ApplicationContext implements the BeanFactory
* ApplicationContext inherits from BeanFactory
* BeanFactory inherits from ApplicationContext
* BeanFactory implements ApplicationContext

```
Answer
 B
 ```
 
Explantion - ApplicationContext is a more preferred way than BeanFactory
In newer versions of Spring, BeanFactory is replaced by ApplicationContext. But BeanFactory still exists for backward compatibility
ApplicationContext extends BeanFactory has the following advantages:
1. It supports internationalization of text messages
2. It supports event publishing for registered listeners
3. Access to resources such as URLs and files

#### 08. Which of the following is not a Spring module?
* AOP
* O/R Integration
* Spring MVC
* HTML/JSP

```
Answer
 D
 ```
 
Explantion - Spring framework includes many modules such as core, beans, context, expression language, AOP, Aspects, JDBC, ORM, OXM, JMS, Transaction, Web, Servlet, Struts, etc.
 
 #### 09. Beans defined in the spring framework are by default ______?
* Abstract
* Singleton
* Final
* Initialized

```
Answer
 B
 ```
 
Explantion - The word “Singleton” in Spring is used for a bean scope, which means that the bean will only be created once for the entire application. 
Singleton usually stands for the GOF (Gang of Four) pattern. It is an object oriented model ensuring that there will only be one instance of a class.

#### 10. Dependency injection or IOC is a _____________?
* Design Pattern
* Framework
* Java Module
* ORM Framework

```
Answer
 A
 ```
 
Explantion - In software engineering, dependency injection is a technique by which one object provides dependencies to another object. 
A dependency is a usable object (a service). An injection is the passage of a dependency to a dependent object (a client) that would use it.

#### 11. What is dependency injection?
* It is a design pattern that implements the Inversion of control (IoC) pattern for software applications.
* It is one of the Spring modules.
* It is a technique to get dependencies from any project.
* It is used to promote loose coupling in code.

```
Answer
 A
 ```
 
Explantion - Dependency Injection is a design pattern that implements the Inversion of Control pattern for software applications.

#### 12. What types of dependency injection does Spring support?
* Based on the constructor and setters
** Based on the constructor, setters, and getters
* Based on setters, getters, and properties
* Based on the constructor, setters, and properties

```
Answer
 A
 ```
 
Explantion - Spring supports constructor-based and setters-based injections.

#### 13. Which of the following statements is correct regarding the Spring Framework?
* The Spring Framework is a heavy-weight solution.
* The Spring Framework is a light-weight solution.
* Both A and B are true.
* None of the above

```
Answer
 B
 ```
 
Explantion - There are many reasons why spring is a lightweight framework.
1. Spring provides you with different modules and allows you to use whatever works best for you. Ideally, the spring JAR file is only 2-3 MB.
2. If you compare Spring with EJB, you have to write much less code and configurations. The beauty of Spring is that you can focus on the business logic whereas in EJB, you have to write a lot of code along with the business logic which makes it cumbersome and tightly coupled.
3. With Spring, you play with POJO which does not depend on a Framework and improves the testability of your code.
4. Spring offers seamless integration with frameworks, third-party libraries, etc.

#### 14. AOP is part of Core Container in the Spring Framework?
* True
* False

```
Answer
 B
 ```
 
Explantion - AOP (Aspect-oriented programming) is not part of Core Container, is one of the key components of the Spring Framework, is a programming approach that allows properties of a program to determine how they are compiled into an executable program. 
AOP complements the OOP rules by also providing modularity. 
AOP breaks down the logic of the program into distinct parts called “concerns”. 
This increases modularity by cross-cutting concerns.

#### 15. The Expression Language is part of the Core Container in the Spring?
* True
* False

```
Answer
 A
 ```
 
Explantion - SpEL stands for Spring Expression Language which is part of Core Container. It is a powerful expression language that supports queries and manipulation of an object graph at bean creation or runtime. 
It is similar to other expression languages such as JSP EL, OGNL, MVEL and JBoss EL, etc., with some additional features such as method calling and basic string modeling.

#### 16. Can we integrate spring with struts?
* Yes
* No

```
Answer
 A
 ```
 
Explantion - Spring is a popular web framework for easy integration with many popular web libraries. 
So the question is: why do we need Spring when we have Struts? 
Spring is more than an MVC framework: it offers many other benefits that are not available in Struts.

#### 17. Spring is a ___________ framework?
* free
* open source
* under license
* proprietary

```
Answer
 B
 ```
 
Explantion - The Spring Framework is open source.

#### 18. What are the different types of Bean injection?
* constructor and setter
* constructor and getter
* getter and setter
* setter, getter and constructor

```
Answer
 A
 ```
 
Explantion - Spring supports both setter and constructor injection.

#### 19. Controller in Spring is a(n)_______________?
* abstract class
* concrete class
* final class
* interface

```
Answer
 D
 ```
 
Explantion - Another way to create a controller in Spring framework is to have a class implement the Controller interface. 
For example:
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;
 
import org.springframework.web.servlet.ModelAndView;
import org.springframework.web.servlet.mvc.Controller;
 
public class ControllerExample implements Controller {
 
    @Override
    public ModelAndView handleRequest(HttpServletRequest rq,
            HttpServletResponse rp) throws Exception {
        System.out.println("Welcome to StackHowTo");
        return new ModelAndView("StackHowTo");
    }
}

#### 20. Which exception class is bound to all the exceptions thrown in Spring applications?
* ArrayIndexOutofBound
* DataAccessException
* NullPointerException
* SpringException

```
Answer
 B
 ```
 
Explantion - DataAccessException is an exception defined by the Spring framework. There are two things to note about DataAccessException. 
First of all, this is an exception. 
Therefore, application code that uses a data access object is not required to wrap every call with a try-catch block, as is the case in JDBC entity beans. 
and EJB 2.x. Second, DataAccessException is useful because it encapsulates the specific exception classes used by the underlying persistence technology and thus keeps the rest of the application independent of the persistence layer.

#### 21. How to explicitly close the IoC container in non-web applications?
* By using shutdownNow()
* registerShutdownHook()

```
Answer
 B
 ```
 
Explantion - registerShutdownHook() in a standalone (non-Web) application:
The @PreDestroy annotation is used on the bean method to be notified when the bean is removed from the context or when the context is being closed.
The stop event is triggered when context.close() or context.registerShutdownHook() is called.
@Component(value="myBean")
public class BeanExample {

    @PreDestroy
    public void destroy() {
        System.out.println("The bean is removed ...");
    }
}

#### 22. How to enable annotations in Spring?
* Add <annotation-context: config /> to the bean configuration.
* Add <annotation-config /> to the bean configuration.
* Add <annotation-context-config /> to the bean configuration.
* Add <contexte: annotation-config /> to the bean configuration.

```
Answer
 D
 ```
 
Explantion - Add <contexte: annotation-config /> to the bean configuration to enable the use of annotations.

#### 23. Which ORM does Spring support?
* Hibernate
* iBatis
* JPA
* All the answers are true
* None of the above

```
Answer
 D
 ```
 
Explantion - Spring supports most ORMs, including Hibernate, JDO, TopLink, iBATIS and JPA.

#### 24. A bean must have an id attribute in the bean configuration file?
* True
* False

```
Answer
 B
 ```
 
Explantion - The id is not a mandatory attribute in the bean configuration file.

#### 25. The ________ class can be extended to create a custom event in Spring.
* SpringEvent
* Event
* ApplicationEvent
* None of the above

```
Answer
 C
 ```
 
Explantion - ApplicationEvent is used to create custom events.

#### 26. How to use <ref> tag in the Spring framework?
* <ref> tag is used with the bean ID.
* <ref> tag is used with a String value.
* Both A and B are true.
* None of the above

```
Answer
 A
 ```
 
Explantion - In Spring, we must use the <ref> tag to inform the Spring container of the object’s dependency.
In Spring, beans can “access” each other by specifying their references in the same configuration file or in a different configuration file. In Spring, we can write several configuration xml files. Our associated bean can be in the same xml or in another xml file.

Example : person-bean.xml
<?xml version="1.0" encoding="UTF-8"?>
<beans>   
    <bean id="personDetails" class="com.jwt.spring.PersonImpl"/>
</beans>

Now, in the XML file below, we refer to “personDetails” configured in the person-bean.xml file. We must therefore use the “ref” tag with the “bean” attribute i.e. <ref bean =" personDetails "/>.

company-bean.xml
<?xml version="1.0" encoding="UTF-8"?>
<beans>   
    ....
    <bean id="companyId" class="com.jwt.spring.Company">
      <property name="perdetails">
        <ref bean="personDetails"/>
      </property>
    </bean>
     ....
</beans>

#### 27. How to define a bean in Spring?
* Use only the following <property />
* Use only the following <constructor-arg />
* Use <property /> or <constructor-arg />.
* None of the above

```
Answer
 C
 ```
 
Explantion -  <bean id="objetB" scope="request" class="a.b.c.classeB"/>

<bean id="objetA" scope="request" class="a.b.c.classeA">
    <constructor-arg ref="objetB" />
    <!-- OR -->
    <property name="bRef" ref="objetB" />
</bean>

#### 28. Which property is replaced by p-namespace in the Spring framewrok?
* <property />
* <constructor-arg />

```
Answer
 A
 ```
 
Explantion - In spring, p-namespace is an XML shortcut to inject a dependency into the bean. p-namespace replaces the <property> tag of XML. 
p-namespace has no XSD definition and exists only in the spring core. We can directly assign the attribute name of the class with p-namespace in the bean tag. 
We can use p-namespace instead of the <property> tag in spring XML. It is easy and clear to use, which will increase the readability of the XML context. 
Suppose we have the following <bean> definition in XML.

<bean id="per" class="x.y.z.Person">
  <property name="name" value="Alex"/>
  <property name="address" value="California"/>
</bean>

We can change the <property> tag using p-namespace as follows.

<bean id="per" class="x.y.z.Person" p:name="Alex" p:address="California"/>

#### 29. Which property is replaced by c-namespace in the Spring framewrok?
* <property />
* <constructor-arg />

```
Answer
 B
 ```
 
Explantion - c-namespace was introduced in spring 3.1. It replaces the old style of constructor-arg. The bean that needs to be configured with c-namespace must have a constructor to accept these arguments.
Example – The old style :

<bean id="std" class="x.y.z.Student">
  <constructor-arg name="name" value="BOB"/>
  <constructor-arg name="age" value="25"/>
</bean>

We can replace constructor-arg using c-namespace as follows.

<bean id="std" class="x.y.z.Student" c:name="BOB" c:age="25"/>

#### 30. What is the purpose of “ApplicationContextAware” in Spring?
* The dependency injection is performed.
* Makes a bean aware of the container.

```
Answer
 B
 ```
 
Explantion - The Bean implementing the “ApplicationContextAware” interface can get the current context of the application and can be used to call any service from the application context.

#### 31. How many proxy types are there in the Spring framework?
* One
* Two
* Three
* Four

```
Answer
 B
 ```
 
Explantion - 
Static
Dynamic

#### 32. What are the features offered by Spring?
* Resource management
* Resource unwrapping
* Exception handling
* Transaction participation
* All the answers are true

```
Answer
 E
 ```
 
#### 33. Choose the correct option:
* The first version was written by Rod Johnson, released in October 2002.
* The framework was first released under the Apache 2.0 license in June 2003.
* The Spring 1.2.6 framework won a productivity award and an innovation award in 2006.
* All the answers are true

```
Answer
 D
 ```
 
#### 34. Choose the correct option:
* The Spring framework is an open source application.
* The Spring framework is a Java platform.
* The Spring framework is used by the .NET framework.
* All the answers are true

```
Answer
 D
 ```
 
#### 35. Spring is an MVC framework based on requests?
* Yes
* No

```
Answer
 A
```

#### 36. What does MVC mean for Spring?
* Model view Controller
* Middle view Controller
* Module view Controller
* None of the above

```
Answer
 A
 ```
 
#### 37. What does AOP mean to Spring?
* Aspect Oriented Programs
* Aspect Oriented Programming
* Aspect Oriente Programming
* None of the above

```
Answer
 B 
 ```
 
#### 38. How to externalize constants from a Spring configuration file or a Spring annotation in the .properties file?
* Using the tag util:constant
* By declaring the post-processor of the ConstantPlaceholderConfigurer bean
* Using the tag contexte:property-placeholder
* Using the namespace c:

```
Answer
 C
 ```
 
Explnation - 1. The <util:constant static-field="constant_name"/> tag is used to reference a Java constant or enumeration in a spring configuration file.
2. ConstantPlaceholderConfigurer does not exist. You can think of the PropertyPlaceholderConfigurer post-processor.
3. The <context:property-placeholder location = "file: /maApp.properties" /> tag enables placeholder replacement $ {…}, resolved from the specified property file.
4. The c: namespace is intended to simplify the constructor syntax (since Spring 3.1) and does not provide such a feature.

#### 39. How many dynamic proxy types are available in Spring?
* One
* Two
* Three
* Four
 
 ```
Answer
 B
 ```
 
Explanation - 
JDK Dynamic Proxy
CGLIB Dynamic Proxy

#### 40. Select the correct statement to reference a Spring configuration file inside the com.stackhowto.myapp package in the example below?
ApplicationContext context = new 
ClassPathXmlApplicationContext("classpath:/com.stackhowto.myapp.config.xml");
* The classpath: prefix can be omitted
* The name of the package with the dot is not well formatted
* The slash before com.stackhowto can be omitted
* All the answers are true

```
Answer
 D
 ```
 
Explanation - 1. When you use the ClassPathXmlApplicationContext, the prefix classpath: is the default prefix. So you can remove it.
2. The location of a resource in Spring, the package separator is a slash and not a dot. Thus, the syntax com/stackhowto/myapp/config.xml should be used.
3. ClassPathXmlApplicationContext starts searching from the root of the class path, whether or not you specify “/”.

#### 41. What is not true about the @PostConstruct, @Resource and @PreDestroy annotations?
* These annotations are specified in the JSR-250
* The context:component-scan tag enables these annotations
* The Spring framework integrates these annotations
* The contexte:annotation-config tag enables these annotations

```
Answer
 C
 ```
 
#### 42. Based on the following Spring configuration file, what are the correct instructions?
<bean class="com.spring.service.CompanyServiceImpl" p:CompanyName="StackHowTo"> 
</bean>
* The namespace p must be declared
* The ID of the bean is CompanyServiceImpl
* CompanyServiceImpl refers to a bean called StackHowTo
* None of the above

```
Answer
 A
 ```
 
#### 43. Based on the following Spring configuration file, what are the correct instructions?
<bean class="com.spring.service.MyServiceImpl"> 
     <property name="repository" ref="jpaDao"/> 
</bean>
<bean class="com.spring.repository.JpaDao"/>
* In the first bean declared on MyServiceImpl, an identifier named myService is missing.
* The second bean declared JpaDao, it is missing an identifier must be named jpaDao
* Both A and B are true.
* Both A and B are false.

```
Answer
 B
 ```
 
Explanation - These beans are anonymous because no identifier is explicitly provided. 
 Thus, the Spring container generates a unique identifier for this bean. It uses the full class name and adds a number to them. 
 However, if you want to refer to this bean by its name, you have to provide a name through the use of the ref element. 
 To be accurate, the second bean has to declare an id jpaDao attribute in order to be referenced by the repository property of the first bean.
 
#### 44. What is usually the case(s) where you usually need to manually instantiate an ApplicationContext?
* In a web application
* In an integration test executed with SpringJUnit4ClassRunner
* In a standalone application started with the main() method
* None of the above

```
Answer
 C
 ```
 
Explanation - 1. In a Web application, ContextLoaderListener is responsible for creating a WebApplicationContext.
2. In a Spring-based integration test, SpringJUnit4ClassRunner creates the application context for you. The @ContextConfiguration annotation is used to specify application context configuration files.
3. In the main method, you must instantiate a class implementing the ApplicationContext interface (examples: ClassPathXmlApplicationContext or FileSystemXmlApplicationContext).

#### 45. What is the name of the bean defined in the following configuration class. Select only one answer?
@Configuration 
public class AppConfig { 

  @Autowired 
  private DataSource ds; 
  
  @Bean 
  ClientRepository clientRepository() { 
  
    ClientRepository cmpRepository = new JpaClientRepository(); 
    cmpRepository.setDataSource(ds); 
    
    return cmpRepository; 
  } 
  
}
* JpaClientRepository
* clientRepository
* Two beans are defined: data souce and repository
* None of the above

```
Answer
 B
 ```
Explanation - The @Bean annotation defines a String bean with the clientRepository id. JpaClientRepository is the implementation class of the bean.
Data source is injected and is not declared in this class.

#### 46. What is the scope of a stateless bean in Spring?
* Singleton scope
* Prototype scope

```
Answer
 A
 ```
 
Explanation - Prototype scope. If the scope is set to prototype, the Spring IoC container creates a new instance of the bean object each time a request for that specific bean is made. 
As a general rule, use the prototype scope for all state-full beans and the singleton scope for stateless beans.

#### 47. How to auto-inject in an attribute a bean by its name?
* With the name attribute of the @Autowired annotation
* Using the unique @Qualifier annotation
* Using the @Autowired and @Qualifier spring annotations
* None of the above

```
Answer
 C
 ```
 
 Explanation - 
 Example:
 public class ClientBean{
  
  @Qualifier("bean1")
  @Autowired
  private MonBean monBean;
  
  ...
  
}

#### 48. What are the main advantages of using Spring when writing unit tests?
* Reuse the Spring configuration files of the application
* Using dependency injection
* Provide mocks for servlet classes
* All the answers are true

```
Answer
 C
 ```
 
Explanation - What are the main advantages of using Spring when writing unit tests?
You do not need the Spring container to write the unit test.
The org.springframework.mock package provides mock classes such as MockHttpSession or MockHttpContext. 
They could be useful for unit testing in the presentation layer and when you are not using a mock framework such as Mockity or EasyMock.

#### 49. Select the correct statement regarding the transactional management of the Spring?
* The transaction manager can be defined with the @TransactionConfiguration annotation
* The method with the @Before annotation is executed outside the test transaction
* The Spring framework test can cancel the transaction of a service configured with the REQUIRES_NEW propagation
* All the answers are true

```
Answer
 A
 ```
 
Explanation - TransactionConfiguration defines class-level metadata for transactional test configuration.

#### 50. Select the correct statement regarding the integration test development with Spring?
* A new Spring context is created for each test class
* To get a reference to the bean you want to test, you have to call the getBean() method of the Spring context.
* The Spring context configuration could inherit from the class super
* The Spring context configuration file must be provided in the parameters of the @ContextConfiguration annotation.

```
Answer
 C
 ```
 
Explanation - 1. The Spring context is cached in the tests, unless you use the @DirtiesContext annotation.
2. With the Spring test module, dependency injection is available when testing. So you can automatically inject the bean to test it
3. By default, a class with the @ContextConfiguration annotation inherits the context configuration file locations defined by the annotation of a superclass. InheritLocations of this attribute allows to change this default behavior.
4. If no context configuration file is provided to the @ContextConfiguration annotation, Spring uses a convention name. It tries to load a file named with the name of the test class with the suffix “-context.xml” (i.e. MyTestClass.xml).

#### 51. In which scope can you create any number of bean instances?
* Request scope
* Prototype scope

```
Answer
 B
 ```
 
Explanation - The Prototype scope extends a bean definition to an unlimited number of object instances.

#### 52. When a bean has a limited scope to an HTTP request, it is called _____?
* Request scope
* Session scope

```
Answer
 A
 ```
 
Explanation - The Request scope extends a single bean definition to a single HTTP request life cycle; that is, each HTTP request will have its own instance of a created bean. Only valid in the context of ApplicationContext.

#### 53. When a bean has a limited scope to an HTTP session, it is called _____?
* Request scope
* Session scope

```
Answer
 B
 ```
 
Explanation - Session scope extends a single bean definition to a single HTTP session lifecycle. Valid only in the context of ApplicationContext in Spring.

#### 54. In which scope a single instance of a bean is created by the IoC container?
* Singleton scope
* Request scope

```
Answer
 A
 ```
 
Explanation - The Singleton scope extends a definition of a bean to a single instance of an object in each IoC container.

#### 55. What is the scope of a stateless bean in Spring?
* Singleton scope
* Prototype scope

```
Answer
 A
 ```
 
Explanation - If the scope is set to prototype, the Spring IoC container creates a new instance of the bean object each time a request for that specific bean is made. 
As a general rule, use the prototype scope for all state-full beans and the singleton scope for stateless beans.

#### 56. What is the correct answer about the bean life cycle in Spring.
* The method with the @PostConstruct annotation is called after the instantiation of the bean and before the setting of its properties.
* The @PreDestroy method of a bean prototype is called when the bean is destroyed.
* The init() method declared in the init-method attribute of a bean is called before the afterPropertiesSet callback method of the InitializingBean interface.
* The method with the @PostConstruct annotation is called before the afterPropertiesSet callback method of the InitializingBean interface.

```
Answer
 D
 ```
 
Explanation - 1. In the life cycle of a bean, the method with the @PostConstruct annotation is called after the property definition step and the BeanPostProcessors#postProcessBeforeInitialization step.
2. Destroy prototype methods of a bean are never called
3. In the life cycle of a bean, the callback method afterPropertiesSet of InitializingBean is called after the method with the @PostConstruct annotation and before the init method declared in the XML configuration file.
4. In the life cycle of a bean, the method with the @PreDestroy annotation is called before the destroy callback of the DisposableBean interface and before the destroy method declared in the XML configuration file.

#### 57. Which one is not correct about the benefits of using Spring when writing integration tests?
* Reuse the Spring configuration files of the application
* Create a mock or a stub
* Be able to use the restoration after the test
* Using dependency injection

```
Answer
 B
 ```
 
Explanation - Mocks or stubs are more common in unit tests than in integration tests. And Spring does not provide any implementation or abstraction of the mock.

#### 58. What is the correct answer about the Spring test module?
* It provides an abstraction layer for open source mock frameworks
* Provides the @Mock annotation
* It dynamically generates mock objects
* None of the above.

```
Answer
 D
 ```
 
#### 59. What are the features of XML <contexte: namespace ?
* Analysis of transactional annotations
* Enable @Aspect annotation detection
* Enable @Autowired annotation
* None of the above

```
Answer
 C
 ```
 
Explanation - 1. Use <tx:annotation-driven> to activate the @Transactional annotation
2. Use <aop: aspectj-autoproxy> to enable detection of the @Aspect bean.
3. Use <contexte: annotation-config> or <contexte: composant-scan> to activate the @Autowiring annotation

#### 60. Which of the following is the classification of different autowire in Spring?
* byName, byType, destructor, and autodetect
* byName, byMethod, constructor, and autodetect
* byName, byType, constructor, and autocorrect
* byName, byType, constructor, and autodetect

```
Answer
B
```

#### 61. The concept of an endpoint in web services is much like that of a controller in web applications.
* True
* False

```
Answer
A
```

#### 62. Spring-WS provides various abstract endpoint classes for you to process the request.
* org.springframework.ws.server.endpoint
* org.springframework.ws.server
* org.springframework.*
* none of the mentioned

```
Answer
A
```

Explanation - Spring-WS provides various abstract endpoint classes for you to process the request and response 
XML messages using different XML processing technologies and APIs. These classes are all located in the
org.springframework.ws.server.endpoint package.

#### 63. Endpoint Classes for DOM:-
* AbstractDomPayloadEndpoint
* AbstractJDomPayloadEndpoint
* AbstractDom4jPayloadEndpoint
* AbstractXomPayloadEndpoint

```
Answer
A
```

Explanation - Endpoint Classes for Different XML Processing Technologies/APIs.

#### 64. If you need to get access to the entire SOAP message, you should write an endpoint class by implementing:-
* org.springframework.ws.server.endpoint.MessageEndpoint
* org.springframework.ws
* org.springframework.ws.server.endpoint
* all of the mentioned

```
Answer
A
```

#### 65. Web services can be invoked through the core template class:-
* org.springframework.ws.client.core.WebServiceTemplate
* JDBC Template
* All of the mentioned
* None of the mentioned

```
Answer
A
```

#### 66. WebServiceTemplate provides a sendSourceAndReceiveToResult() method that accepts arguments:-
* java.xml.transform.Source
* java.xml.transform.Result
* all of the mentioned
* none of the mentioned

```
Answer
C
```

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>
