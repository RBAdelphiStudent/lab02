# Lab 02 -- Chapter 01

## Define the following terms:
* object, State or behavior (instance) of a class.
* class, blueprint (code) that defines how to create an object.
* instance, Specific realization of any object.
* method, A collection of statements, in a class, used to manipulate (mutators) or access (accessors) information from an object of that class (behaves like a function in mathematics)
* signature (or header), the name of a method and the parameter types found in the method's header. I.e. the following signature changes the size of the instance `box` of class `Box` and does not give an output.
```
void changeSize(Box box)
```
* parameter, an input of the method. I.e. `box` is the parameter in the example above
* type, a type is used to specify what values a parameter or variable is allowed to take/accept (examples include int, boolean, and double, alongside several other types). I.e. it defines what values a parameter or variable is allowed to be.
* state, - the state of an object consists of all its values defining it; a set of values describing an object
* source code, the collection of commands compiled into an executable program and used to define the fields (structure) and methods (behavior) of each class
* return value, a result value returned from an accessor method; return values are used to get information on objects via methods- output of a method
* compiler- a program that translates a source code written in a particular programming language into a machine language that can be understood and used by a computer (forces computer to read instructions in code)

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
* byte- an 8-bit signed two's complement integer data type which has a value that can range from -128 to 127; it is frequently used in arrays to save data
* short- a 16-bit signed two's complement integer data type which has a value that can range from -32,768 to 32,767; like bytes, they are often used to save data in arrays while saving memory
* int- a 32-bit signed two's complement integer data type which has a value that can range from -2^31 to (2^31)-1. It is often used to store data used in arithmetic operation involving integers.
* long- a 64-bit signed two's complement integer data type which has a value that can range from -2^63 and 2^63-1. Longs are frequently used to substitute for ints when values larger than ints can store are needed
* float- a single precision 32-bit IEEE 754 floating point used to store decimal numbers; it stores less decimal places than a double, but takes up less memory, so it is often used to save decimal numbers as data in arrays
* double- a signle precision 64-bit IEEE 754 floating point used to store decimal numbers; it can store more decimal places than a float.
* boolean- a data type with only two values, true and false, which is typically used as a flag to track true/false conditions
* char- a data type that stores the value of a single character, which ranges from '\u0000' to '\uffff'
* String- a data type whose value consists of a series of characters (example: "a string of data")

## What are the types of the following values?

* 0: byte, short, int, long, double, float
* "hello": String
* 101: byte, short, int, long, double, float
* -1: byte, short, int, long, double, float
* true: boolean
* "33": String
* 3.1415: float, double

## What would you have to do to add a new field, for example one called name, to a circle object?
* To add a new field (name) to a circle object, I would add this code under the header for the circle class. I could later define this field for specific instances of an object.
```
private String name;
```

## Write the header for a method named send that has one parameter of type String, and does not return a value.
```
public void send(String message);
```

## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
```
public int average(int variable1, int variable2){
```

## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
* The book I am currently reading is an object that is a member of the class `Books`.

## Can an object have several different classes? Discuss.
*  In Java, an object can have multiple classes if the class of an object falls within a certain superclass. Otherwise, though a Java object can only be considered one class. It cannot be considered a member of different classes unless one is a subclass of the other. An object can call on and interact with multiple classes, but it is only considered one class.
