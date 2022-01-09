# JavaInterviewQuestions

singleton class
------------------
can create only an object that can be shared by all other classes.
--------------

interface vs abstract class
----------------------------
Abstract class:Abstract+Non abstract methods,No Multiple inheretence,private,protected.
interface:only abstract methods,Multiple inheretence,public methods.
--------------------------------------------------------

ArrayList and vector
----------------------
ArrayList:not sychronized.(any number of thread),non lagacy,fast,iterator
Vector:sychronized(one time one thread),lagacy class,slow,iterator or enumeration.
-------------------------------------------------------------

String,StringBuilder,StringBuffer
----------------------------------
String:immutable,non-extendsable
StringBuffer:muttable(sychronized),thread safe
StringBuilder:muttable(non-sychronized),non thread safe
---------------------------------------------

Exectption
----------------
Runtime:unchecked(null pointer,Arrayoutofbound,Airtmetic Exception)
compile time:checked(file not found,IOException,SQLExecption,classnotfound,interupped)
try(Risky code),catch(Exectption),finally
-----------------------------

Method overloading
-------------------
parameters are different,compile time polymorphism
-----------------------
Method overriding
---------------------
parameters are same(change the content),run time polymorphism
-------------------------

this vs super
------------
super: parent class data members.
this:current class instance veriable

super():parent class constuctor
-----------------------------------

== and equals
-------------
== (reference comparision)
equals(content comparision)
------------------------------

Thread
---------
runnable inteface
extending Thread class
strat()
stop()
join()
resume()
notify()
sleep()
suspend()
wait()
--------------------------
JDK>JRE>JVM
-------------------

Fuctional Interface in java
-------------------------------
A functional interface is an interface that contains only one abstract method.
----------------------------------------------------------------------------------

Cursor
-------
1)Enumeration 2)Iterator(I) 3)ListIteator.

Enumeration:
--------------
only for lagacy classes.
hasMoreElements.
nextElement.
---------------------
Iterator(It is applicable for any collection univeral cursor)
--------------------------------------------------------------
hasNext,Next,remove.(No backword direction)
--------------------
ListIteator
---------------
only for list interface and its child classes.(move backword and forword)
remove,set,add.
----------------------------------------------------
scope
------
private<default<protected<public
-----------------------------------
protected
--------------
<default>+kids
-----------------------
Demond Thread
Green Thread
--------------------
try:risky code
catch:to maintain exception handling code.
finally:to maintain cleanup code.
throw:to hand over created exception
throws:object to the JVM manually to delegate
---------------------------------------------------
9 key interface
-----------------
1)collection
2)List
3)Set
4)SortedSet
5)Navigableset
6)Queue
7)Map
8)Sorted Map
9)Navigable Map
--------------------------------
CompareTo()
obj1>obj2 // -ve 
obj2<obj3 // +ve
obj1=obj2 // 0
-----------------------------------------
Comparator vs Comparable	
---------------------------
Comparator:customize sorting order,java.util,equals(),Compare(),Rule based application.
Comparable:Default nature sorting order,java lang,CompareTo(),All wrapper classes and string.
------------------------------------------------------
1xx->information 2xx-->sucess 3xx-->Redirectional 4xx-->client error 5xx-->server error.
---------------------------------------------

Stream API(1.8v) for collection and arrays.
-----------
Lambda,filter,Map,Predicate,consumer,suppiler,Min(),Max(),ForEach(),toArrays(),Stream.of()
--------------------------------------
List.of(),Arrays.asList(),
------------------------------
5 Ways to build Stream
---------------------------
Stream.empty
Stream.of(names)
Stream.builder().build()
Arrays.stream()
List.Steam()
----------------------
Filter(predicate(a boolean value))
--------------------------------------
Map()
-----------------
Methods and varibales:stack
object:heap memory.
---------------------------
PreferenceChangeListener
object class 
1)toString()
2)hashCode()
3)wait()
4)wait()
5)wait()
6)equals()
7)clone()
8)Notify
9)NotifyAll
10)getClass()


HashMap contains an array of Node(Hashing)
int hash
k key
v value
Node next

hashCode()
equals()
A bucket= number of buckets * load factor
----------------------------------------------
