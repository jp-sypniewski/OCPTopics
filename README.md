## Topics

#### Loops (for, forEach) *[Steve]*

Sometimes a programmer needs to repeat a section of code, and do so a certain number of times.  The for loop provides this functionality, with the forEach loops taking this further and loops over a collection of objects without explicit definition of the size of the collection.

#### Packages/Imports *[Kent]*

Packages are mechanisms through which programmers encapsulate a group of classes, sub-packages, and interfaces.

The import is the mechanism through which classes can access classes outside of their package.

#### Access Modifiers *[Travis]*

Access modifiers define the visibility of fields and methods within a class.  This defined visibility impacts class and package design, but provides protection that data is only manipulated by objects which can access the data.

#### Constructors

The special method within Java used to initialize an instance of an object.  There's something important about that *new* keyword.

#### Inheritance *[Gabe]*

An important idea behind object oriented programming, inheritance is a mechanism through which one object acquires the properties and behaviors of a parent object.  Inheritance represents the *IS-A* relationship, also known as a parent-child relationship.

#### Overriding *[Marcus]*

In any object oriented programming language, overriding is a feature that allows a subclass or child class to provide a specific implementation of a method provided by the parent.  The name, parameters, and return of the override must match the parent classes methods.

#### Overloading *[Frank]*

Related to compile-time polymorphism, overloading allows different methods to have the same name, but different input parameters.

#### Parameter Passing *[Neal]*

Neal is here to tell us why Java is <sarcasm>definitely, 100%, pass by reference</sarcasm>.

#### References, Heap, GC, this

References are how we refer to objects in Java.  These objects are (generally) stored on the heap, with the objects becoming eligible for garbage collection when there are no longer references pointing to the object.  Objects may also use the 'this' keyword to self-refer where needed.

#### Static (when, where, why), Final *[Josh]*

Static is a non-access modifier keyword in Java, which allows for access before any objects of the class are created and without reference to any object.

Final is also a non-access modifier keyword in Java.  The keyword provides for constant variables, prevention of method overriding, and prevention of class inheritance.

#### Arrays - Single Dimension *[Erin]*

The array is a group of like-typed variables that are referred to by a common name.  The single dimensional array is simply a group of objects, as compared to the multidimensional array which is groups of groups of objects (potentially cascading further than two levels...).

#### Arrays - Multi Dimension

Again, the array is a group of like-typed variables referred to by a common name.  With multidimensional arrays, we have groups of groups of these like-typed variables.

#### Maps, Sets, Lists

All implementations of the Collection<E> interface, these types of objects provide better functionality than the array.

#### Wrappers *[Matt]*

Classes that provide a way to use primitive data types as objects.

#### Casting *[Kai]*

Casting provides the programmer with a way to change the reference type of an object.

#### String, StringBuilder *[Skyler]*

Both classes that handle sequences of characters, String and StringBuilder are important classes in Java.  The String class, though, represents immutable sequences of characters.

#### Comparator, Comparable, Lambda *[George]*

Java provides the Comparator and Comparable interfaces to sort objects.  While comparable objects directly compare themselves, comparator is an external object to the element type being compared.  As functional interfaces, lambdas may be used to specify how the interfaces should compare objects.

#### Varargs *[Caleb]*

Varargs is Java's feature that simplifies the creation of methods that need to take a variable number of arguments.  While this is commonly seen within the main method declaration, varargs may also be used within other methods.

#### Field v Local Variables *[Luke]*

Within a class, a programmer may use variables in a wide variety of ways.  If variables are declared as a member of a class, they are field variables.  If variables are declared within a method, they are local variables.
