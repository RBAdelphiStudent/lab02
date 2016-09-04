# Lab 02 -- Chapter 01

## Define the following terms:
* object, the parts that define the model a program builds- an instance of class
* class, a set of data fields used to create objects
* instance, roughly synonymous with object; used to reference objects as instances of a particular class
* method, any operation used to manipulate and communicate with objects
* signature, the name of a method and the paramater types found in the method's header
* parameter, additional values used to further define how a method communicates with or manipulates an object
* type, a type is used to specify what values a paramater is allowed to take/accept (examples include int, boolean, and double, alongside several other types)
* state, - the state of an object consists of all its values defining it
* source code, the text/code used to define the fields (structure) and methods (behavior) of each class
* return value, a result value returned from a method; return values are used to get information on objects via methods
* compiler- a program that translates a source code written in a particular programming language into a machine language that can be understood and used by a computer

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

* 0: Int
* "hello": String
* 101: Int
* -1: Int
* true: boolean
* "33": String
* 3.1415: Float

## What would you have to do to add a new field, for example one called name, to a circle object?
* To add a new field (name) to a circle object, I would add this code under the header for the circle class. I could later define this field for specific instances of an object.
* String name;

## Write the header for a method named send that has one parameter of type String, and does not return a value.
* public void send(String message);

## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
* public average(int variable1, int variable2){

## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class. 
* The book I am currently reading is an object that is a member of the Book class.

## Can an object have several different classes? Discuss.
*  An object
