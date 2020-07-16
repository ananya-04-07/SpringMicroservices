# SpringMicroservices

--Date ---> 13-07-2020
Effective java ---

Item 43:  Prefer method references to lambdas
Item 44:  favor the use of standard functional interfaces
* In this two item i have learnt about functional inteface, Template method pattern, LinkedHashMap removeEldestEntry.
* Went through one lecture of lambda expression for deep knowledge  https://www.youtube.com/playlist?list=PLqq-6Pq4lTTa9YGfyhyW2CqdtW9RtY-I3

Spring Microservices in action----
* Completed half of the 2nd Chapter and learn about @SpringBootApplication, @RestRepository, @RequestMapping annotation.(already went through this topics on video lectures)


===================================================================================================================================================================

Date ---> 14-07-2020

item 45: Use stream judiciously
* In this i have learn when to use Stream, and get to know about few functionality of stream such as stream.iterate(),Stream.of() etc.

------------------------------------------------------------------------------------------------------------------------------------
Spring Microservices In action 
* Learn about handling of pom.xml file

------------------------------------------------------------------------------------------------------------------------------------
Elasticsearch
* Introduction to Elasticsearch.


===================================================================================================================================================================

Date -----> 15-07-2020

item 46 : Prefer side effect free functions in streams

* for deep undestanding of this item, i have gone through Stream course https://www.youtube.com/watch?v=5duxFiseLRE
* gone through few links for better understanding of toMap() overridden methods
* In this gone to know that we cannot use forEach() method to perform the computation.

Item 47 : Prefer Collection to Stream as a return type

* left behind few concept of item 45, which is being used in item 47 so have to go through item 45 again.
* In this get to know the lazy nature of stream.
* learnt about adapter methods.
* adapter mrthod for iterable to stream and stream to iterable
* why we need to return stream when there are infinite sequence of data instead of Collection.


================================================================================

Date ---> 16-07-2020

item 48:  Use caution when making streams parallel

* Get to know the effect of using parallel stream CPU performance get better in few scenarios but we might have to see undesirable result.
* learn about forEachOrdered.

Item 49: Check parameters for validity

* In this i have learnt about the validation of parameter of method before using it.
* got familiar with @Nullable and object.requiredNotNull() method.
* non public method can check their parameter using assert
* assert will be activated only when we enable the assert flag by passing -ea flag to java command.


Item 50: Make defensive copies when needed

* when object are shared with other object and the former are modified by later causing unexpected behaviour, then we need defensive copy.
* when can't use clone method to make defensive copy because at some places the objects are mutable and the clone method is not guarenteed to return an object
whose class is the required class instead it could return AN INSTANCE OF An untrusted subclass.
* for security purpose we should code defensively by making the code unmutable.
* if the code is not unmutable then with the help of defensive copying we have make it mutable so that client won't be able to chance the invariant of object.

Item 51: Design method Signature Carefully

* in this i have learnt mathod should be named appropriately.
* there should not be more than 4 parameter.
* if requirement of more than 4 parameter is there then we can solve it by using 3 techniques:-
      1) break the function into sub function in which required parameter list is the sublist of formal parameter list.
      2) with the help of helper class to hold group of parameter.
      3) Builder pattern.
      
Item 52 : Use overloading judiciously
      half of the item is completed


