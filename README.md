# SpringBasics AOP using Around Advice

Spring supports the use of AOP advice to intercept method calls through the use of the org.aopalliance.intercept.MethodInterceptor class. 
This class provides the ability to define an around advice, which is a type of advice that is applied before and after a join point.
An around advice is a type of advice that is used to modify the behavior of a join point.
In the context of Spring AOP, an around advice is implemented using the MethodInterceptor interface.
The MethodInterceptor interface provides a single method, invoke(), which is used to implement the around advice.
This method is called before and after the target method is executed. 
The invoke() method can be used to perform any type of logic that needs to be executed before and after the join point.
