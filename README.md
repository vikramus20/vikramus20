- 👋 Hi, I’m @vikramus20
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
vikramus20/vikramus20 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
JAVA
=========================

1. Difference between RowSet and ResultSet?

2. PreparedStatement and Statement.

** 3. Difference JPA and Hibernate.
	- Java Persistence Api is a specification and Hibernate is an implementation to JPA. It provides bunch of classes and Interface which is implemented by Hibernate. 

4. First Level Cache and Second Level Cache.
** 5. StringBuilder and String Buffer.
	-StringBuilder is fast but StringBuffer is ThreadSafe
	-String is Immutable whereas StringBuilder and StringBuffer are Mutable.
6. ?

7. What is angular directives and name some angular directives.
	-1. Component 
	-2. Attribute - ngClass, ngStyle, ngModel
	-3. Structural - ngIf,ngIfElse,ngSwitch,ngFor

8.How to store data in a Hashset if you have to maintain unique data according to a Object field uniquely like email?
 By OverRiding the Method of HashSet.

** 9. What is functional interface? Differentiate functional interface with interface.
    - Is a type of interface which has only one abstract method.

10. Immutable Class. List immutable class.
	- String
	- All Other Wrapper Classes of primitive types like float,double etc.
11. What is thread safe in java.
12. Fail Safe and Fail fast.
13. List Annotations used in Spring boot.
14. Different ways to use Autowire in Springboot.
	-Field
	-Setter
	-Constructor
15. Eureka Server Client Annotation in Springboot.
	-@EnableEurekaServer
	-@EnableEurekaDiscoveryClient
	-@EnableEurekaClient
16. TreeMap
17. LinkedHashMap
18. HashMap and HashTable difference
19. How establish trust between API. 
    - Oauth, Okta, 

20. Transactional and isolation level in JPA Repository.
   - @Transactional(isolation = Isolation.SERIALIZABLE)
   - @Transactional(isolation = Isolation.READ_UNCOMMITTED)
   - @Transactional(isolation = Isolation.READ_COMMITTED)
   - @Transactional(isolation = Isolation.REPEATABLE_READ)
source: https://www.baeldung.com/spring-transactional-propagation-isolation	

21. What is Dirty Read? Question form Transaction Isolation   - hiefANGULAR

22. Difference between @autowired and @inject 

23. How to Manage Database connection pool in Spring boot?

24. Bean Life Cycle in Spring boot.

25. Default method in java 8.
    - Methods which has body can be put inside an interface known as Default Method. uses default keyword. 

26. Default ServletFilter in Spring boot.

27. Difference between SOAP and REST.

28. Similarities between SOAP and REST.

29. Transactional activity in Microservice. (Design Pattern)	
	- Two Phase Commit (2PC)
	- SAGA

30. What is reduce in Java Stream?

31. SOAP and EJB difference.

32. Can we have normal method in interface in Java 8.

33. List SOAP methods

34. Future and Completable future.

35. Logger level.
	-ALL
	-DEBUG
	-INFO
	-WARN
	-ERROR
	-FATAL
	-OFF
	-Trace

36. Thread executor.

37. Isolation types in dbms.

38. Thread Executor.

39. Method of SOAP.
	-GET and POST
40. SOLID?

41. Design Pattern Of Logger.

43. A Popular Design Pattern used in Spring boot created by Spring Team.

44. JSR @Valid (implemented by whom?)

45. What is Zuul?

46. What is Splunk?

47. What is AutoConfiguration in Spring boot.

48. How to create War file using Maven and Gradle.
 
49. DependencyManagement in POM file.

50. Global Exception Handling in JSP application.

51. Write a program in stream to find out the highest salary of an employee from a list of employees.

52. Write a program in Java to Reverse the number with the sign.

53. Convert to a single list List<List<String>> to List<String>.

54. PreparedStatement.executeBatch() for inserting large amount of data in single hit.

55. 12 Factors of Microservices.

56. Cons of Microservices.

57. Volatile in Java.

58. How do you handle functional error in services.

59. Java 11 Features.

60. What is Sharding? Explain vertical and Horizontal sharding.

61. What is Partioning in oracle db?

62. What is ResponseEntity object in Spring boot?

63. What is difference between @GetMapping and @RequestMapping in spring boot?

64. 


==========================
1. What is Angular?
   -Angular is Open source Javascript UI Framework written in Typescript which maintained by Google. 
	It provides features to design and develop Modern SPA for Client Side.  

2. Component Life Cycle Hooks.
	Constructor
	-ngOnChange
	-ngOnInit
	-ngDoCheck
		-ngAfterContentInit
		-ngAfterContentChecked
		-ngAfterViewInit
		-ngAfterViewChecked
	-ngOnDestroy

3. List Angular Directives.
   -Three different types of Directive:
	-Component: 
	-Attribute: ngClass,ngStyle,ngModel
	-Structural: ngIf,ngIfElse,ngSwitch,ngFor
4. What is Typescript and how it works



GIT QUESTIONS
==========================
1. Git squash
2. cherry pick


Microservice
==========================
1. What is microservice.
   -Microservice is Architectural development style of creating autonomous, self contained containerized, independent application.
2. Advantages of microservice.
   -Autonomous and Independent process.
   -Self Contained.
   -Generally Containerized
   -Multiplatform and Freedom to choose language best suited.
3. What is CDC.
   - It is a Contract between Service Provider and Service Consumer.
4. What is REST/RESTFUL?
   - It is 
5. Distributed Transaction in Microservices.
   Url: https://developers.redhat.com/blog/2018/10/01/patterns-for-distributed-transactions-within-a-microservices-architecture#possible_solutions
   - 2pc pattern (2 Phase Commit)
	-Prepare & Commit
   - Saga pattern

6. Load Balancer

7. Different Types of Microservice Test
	-Functional
	-Load
	-Resilency
source: https://www.parasoft.com/blog/what-are-different-types-of-tests-for-microservices/

8. What is Zuul.
Zuul Server is an API Gateway application. It handles all the requests and performs the dynamic routing of microservice applications. It is also known as Edge Server. Zuul is built to enable dynamic routing, monitoring, resiliency, and security.

Database
==========================
1. Dirty Read
2. How to find the second highest salary from the list of empoyee records.
	



*******************************
Questions Got from Recruiters:
*******************************
   JAVA AND MICROSERVICES
###############################

1. Which microservices design pattern have you worked on?
	-API Gateway
	-Aggregator
2. How to load balance the microservices request?
3. How to trace each microservices working properly or not?
4. Java code to reverse the alphabet in the string without touching special characters and numbers.
5.what is a singleton design pattern? 
6. How to achieve complete immutability?
7. Collection- hashmap and hashset internal implementation.
 8. What different annotations, you have used in your project.
Spring bean life cycle
9.Explain your project architecture and ur current roles in the project
10.how multiple microservices are connected
11. if a microservice is down, how do you handle it
12.working on multithreading experience, worked on futures in multithreading.
feature of java 8
13.coding example using Lambda and functional interfaces, how to do u find even numbers and add two numbers using the functional interface
14. explain the total flow of Restfull api call from making a call and returning the response.
15. Experience with sql and plsql programming, difference between primary and unique key
16. annotation used for writing native queries.

write program

 Questions:

find the second largest number in array

some questions pertains to Microservices, how u r work on security

how do you handle firewall in API gateway

api gateway


Main Focus at the time of interview:

1.       Why Java core ?

2.       why we need spring boot?

3.       What is the difference between a microservice vs monolithic application?

4.       spring boot annotations

5.       difference between hashmap and concurrenthashmap

6.       multithreading runable and concurrenthashmap

 

Customer Feedback on our previous selected candidates:

1.       Java/ Java 8 - 8/10

2.       J2EE - 7/10

3.       Microservices - 7/10

4.       Spring Boot - 9/10

5.       Cloud Concepts – 8/10

6.       DB - 9/10

 

Some Add ons:

1.       Functional interface java

2.       Junit test case 

3.       Seralization in java 

4.       Threads in java 

5.       5.java 8 features 

6.       Restful web services 

7.       7. collections api in java 

8.       Difference between @autowired and @inject 












