![GitHub last commit](https://img.shields.io/github/last-commit/Starcode71Ooze/JAVA-JET.svg?color=light%20green)  ![Github coverage](https://img.shields.io/badge/Java-100%25-blue.svg)

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRqe9qPKBN1TNd-HhAPNCx5_dnp8K-K4wS3mouErVI3zt-qLnKi)
# Java
Java is one of the most popular and widely used programming language and platform.It is fast, reliable and secure.Also java is *object-oriented programming* language.Java is *statically type language* (because the type of data is predefined as part of the programming language and all constants or variables are defined for a given program).
### Data Types:
They are basically of two types:
1) Primitive data type
2) Object data type

Primitive consists of boolean,byte,char,short,int,long,float,double.Whereas Object consists of programmer created types.
### Variables in Java:
A variable is the name given to a memory location. It is the basic unit of storage in a program.
For declaring a variable it includes data type,variable name and value.
For Eg. `int cost = 20;`
Here `int` is data type ,`cost` is variable name and `20` is value.
### Java Identifiers:
In Java, an identifier can be a class name, method name, variable name or a label.There are certain rules to define java identifiers:

1. Only alphanumeric characters are allowed as identifiers i.e. [A-Z], [a-z], [0-9] and '$', '_'.

1. Identifiers should not start with digit[0-9].

1. Special characters like @ and & are also not allowed.

1. [*Reserved words*](https://www.computerhope.com/jargon/j/java_reserved_words.htm) can't be used.

Here is the first java program-[*Hello World*](https://github.com/Starcode71Ooze/JAVA-JET/blob/master/HelloWorld.java)

### OOP Concept:
Java is an object oriented programming language.The main aim of OOP is to bind together the data and the functions that operate so that no other part of the code can access this data except that function.
<dd>OOPs Concept INCLUDES: </dd>
1)<B>Polymorphism-</B> Way to differentiate between entities with the same name efficiently.

  For example:[here](https://github.com/Starcode71Ooze/JAVA-JET/blob/master/polymorphism.java)

2)<B> Inheritance-</B> Mechanism by which one class can inherit the features of another class.

3)<B> Object-</B> It the most basic unit of OOPs.An object consists of : 
 
 - STATE: It is represented by attributes of an object. It also reflects the properties of an object.
 
 - BEHAVIOUR : It is represented by methods of an object. It also reflects the response of an object with other objects.
 
 - IDENTITY: It gives a unique name to an object and enables one object to interact with other objects.
 
 A simple program to explain the concept of object can be found [here](https://github.com/Starcode71Ooze/JAVA-JET/blob/master/Object.java).

4)<B>Classes-</B>Class is a user defined blueprint or prototype from which objects are created.It shows the set of properties that are common to all objects of same type. In general, class declarations includes:

- MODIFIERS : A class can be public or has default access.

- CLASS NAME: The name should begin with a letter <B>(capitalized by convention).</B>

- SUPER CLASS: The name of the class’s parent (superclass),preceded by the keyword extends.

- BODY: The class body surrounded by braces, { }.
 
 A simple program to explain the concept of classes can be found [here](https://github.com/Starcode71Ooze/JAVA-JET/blob/master/Class.java).

#### NOTE: When class is defined, only the specification for the object is defined; no memory or storage is allocated.To access members defined within the class, you need to create objects.

Example of Class and Object together is [here](https://github.com/Starcode71Ooze/JAVA-JET/blob/master/Class%20and%20Objects.java).

### Object Cloning in Java
Cloning basically means creating a exact copy of an object.The clone() method of Object class is used to clone an object.
The java.lang.Cloneable interface must be implemented by the class whose object clone we want to create.Else clone() method generates CloneNotSupportedException.

Syntax of the clone() method: 

    protected Object clone() throws CloneNotSupportedException
    
The clone() method is defined in the Object class.
#### *Why do we need this clone() method??*
This clone() method saves the extra processing task for creating the exact copy of an object. If we perform it by using the new keyword, it will take a lot of time that is why we use object cloning. 
Example of clone() method is [here](https://github.com/Starcode71Ooze/JAVA-JET/blob/master/Class%20and%20Objects.java).
  
### Java.lang.StringBuffer.appendCodePoint() Method *{RARELY USED}*
This method is used to append the string representation of the codepoint argument.The syntax:
public StringBuffer appendCodePoint(int cp).

###### PARAMETER:

codePoint − This is a Unicode code point.

###### RETURN VALUE: 

The method returns this object after appending the string represented by the codepoint.







