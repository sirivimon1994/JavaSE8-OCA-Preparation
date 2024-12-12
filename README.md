# Java OCA SE 8: Study Guide

## 1. Primitive Data Types
**Overview:** List all the primitive data types in Java and their correct names.  
`byte`, `short`, `int`, `long`, `float`, `double`, `char`, `boolean`

**Details:**  
- Explain size, range, and default values of each primitive type.

## 2. Comparison Operators
**Overview:** Comparison operators used for checking equality or relational conditions.  
`==`, `!=`, `>`, `<`, `>=`, `<=`

**Details:**  
- Discuss their use in expressions and comparisons between primitive types and objects.

## 3. Arithmetic Operators
**Overview:** Operators used for mathematical calculations.  
`+`, `-`, `*`, `/`, `%`

**Details:**  
- Describe how they work with numeric types and their precedence.

## 4. Control Structures
**Overview:** Conditional and loop constructs.  
`if`, `else`, `switch`, `while`, `for`, `do-while`

**Details:**  
- Provide examples and explain how they can be nested.

## 5. Simple Arrays
**Overview:** Declaring and using arrays.  
`int[] arr = new int[10];`

**Details:**  
- Discuss initialization, access, and common operations on arrays.

## 6. Distinguishing Between Classes, Objects, and References
**Overview:** Understanding the distinction.  
- **Class:** Template for creating objects.  
- **Object:** Instance of a class.  
- **Reference:** Variable that holds the address of the object.

**Details:**  
- Clarify object creation, initialization, and referencing.

## 7. Access Modifiers (Visibility)
**Overview:** All visibility modifiers in Java.  
`public`, `private`, `protected`, and default (package-private)

**Details:**  
- Explain how they control access to classes, methods, and fields.

## 8. Constructors
**Overview:** Constructors in Java and their role.

**Details:**  
- **No-argument constructor:** Automatically provided if none is defined.  
- **Parameterized constructor:** Defined by the programmer to initialize objects.  
- **Inheritance and Constructors:** How constructors are called in subclass instantiation.  
- **Super Constructor Call:** `super()` in constructors.

**Example:**  
How inheritance affects constructor calls in derived classes.

## 9. Abstract Classes
**Overview:** Characteristics of abstract classes.  
- Cannot be instantiated directly.  
- Can have abstract (unimplemented) and concrete methods.

**Details:**  
- Explain the use case of abstract classes and when to use them.

## 10. String Class
**Overview:** Understanding the String class in Java.  
- **Immutable Class:** Once created, the value of a String cannot be changed.  
- **Common methods:** `length()`, `charAt()`, `substring()`, `toLowerCase()`, `toUpperCase()`.

**Details:**  
- Emphasize string concatenation, interned strings, and performance considerations.

## 11. Reference Type Casting
**Overview:** Casting between reference types.  
- **Casting up (Upcasting):** Casting to a superclass.  
- **Casting down (Downcasting):** Casting to a subclass.

**Details:**  
- Explain when casting compiles, when it throws exceptions (e.g., `ClassCastException`), and when it’s safe.

## 12. Varargs Methods
**Overview:** Methods that accept variable numbers of arguments.  
Syntax: `public void method(int... nums)`

**Details:**  
- Explain how to use varargs and the limitations (only one vararg parameter per method).

## 13. Predicates and Lambdas
**Overview:** Functional interfaces and lambda expressions.  
**Predicate example:** `Predicate<Integer> isEven = n -> n % 2 == 0;`

**Details:**  
- Discuss the use of lambdas with functional interfaces and predicates for filtering and condition-checking.

## 14. Simple ArrayList API
**Overview:** Using the `ArrayList` class.  
Common methods: `add()`, `remove()`, `get()`, `size()`, `isEmpty()`

**Details:**  
- Demonstrate how to work with `ArrayList` to store and manipulate data.

## 15. Polymorphism
**Overview:** The ability of different objects to respond to the same method in different ways.  
- **Method Overloading:** Same method name, different parameters.  
- **Method Overriding:** Same method signature, different implementations in subclasses.

**Details:**  
- Example with method overriding and polymorphic behavior.

## 16. Exceptions
**Overview:** Handling errors in Java using exceptions.  
`try-catch`, `finally`, `throw`, `throws`

**Details:**  
- Discuss checked vs. unchecked exceptions, how to handle multiple exceptions, and how to create custom exceptions.
