# Software Design Patterns
Let's learn all type of software design patterns and their importance.

## Introduction
Design pattern is a very important section of Software Engineering, which is a general and reusable solution to a commonly occurring problem within a given context in software design. Rather than a complete finish product to code, it is a concept or idea or template that we are using in different situations to solve different problems in the process of software design.

### Different Design Patterns
All design patterns are grouped into 3 groups
* #### Creational Design Pattern

    * This design patterns deals with object creation mechanisms, which mechanism is suitable for the situation. 
    * Used in scenarios when system should not be dependant on, 'how objects are created?'.
    * The basic object creation technique may complecate the design and create complexity for developers, where creational design patterns solve this problem by controlling the object creation process.
    * This design patterns allows you to reuse other people’s knowledge.
    * All Creational Design Patterns are based on two common ideas,
      * They encapsulate knowledge about which concrete class the system should use.
      * They hide, how instances of these concrete classes are created and combined.
    
* #### Structural Design Pattern

   * The Sructural Design Patterns ease the design by identifying a simple way to realize the relationship among entities.
   * Sructural Design Patterns are about organizing different classes and objects to form large structure and provide new functionalies without any change in the existing design structure.
   * Structural Design Patterns depends on two programming concepts, Inheritance and Interface to allow multiple classes and objects to work togather and form a single working structure.
    
* #### Behavioural Design Pattern

   * Behavioural Design Patterns are concerned with object interaction and responsibilities
   * The interaction between the objects should be in such a way that they can easily talk to each other and still should be loosely coupled.
   * The implemantation and the client should be loosely coupledin order to avoid avoid hard coding and dependencies.
   

| # | Creational Design Pattern | # | Structural Design Pattern | # | Behavioral Design Pattern |
| - | ------------------------- | - | ------------------------- | - | ------------------------- |
| 1 | [Factory Method * ](#factory-method) | 7 | [Adapter * ](#adapter) | 15 | [Chain of Responsibility](#chain-of-responsibility) |
| 2 | [Abstract Factory](#abstract-factory) | 8 | [Bridge](#bridge) | 16 | [Command](#command) |
| 3 | [Builder * ](#builder) | 9 | [Composite](#composite) | 17 | [Interpreter](#interpreter) |
| 4 | [Object Pool](#object-pool) | 10 | [Decorator](#decorator) | 18 | [Iterator](#iterator) |
| 5 | [Prototype](#prototype) | 11 | [Facade](#facade) | 19 | [Mediator](#mediator) |
| 6 | [Singleton * ](#singleton) | 12 | [Flyweight](#flyweight) | 20 | [Memento](#memento) |
|  |  | 13 | [Private Class Data](#private-class-data) | 21 | [Null Object](#null-object) |
|  |  | 14 | [Proxy](#proxy) | 22 | [Observer * ](#observer) |
|  |  |  |  |23 | [State * ](#state) |
|  |  |  |  |24 | [Strategy * ](#strategy) |
|  |  | | | 25 | [Template method](#tempate-method) |
|  |  | | | 26 | [Visitor](#visitor) |

(*) - Important Software Design Patterns


1. #### Factory Method

   * Factory method design pattern uses a factory method as an interface to create objects instead of using a direct instantiation of objects, using 'new' keyword.
   * Define an interface or abstract class for creating an object and let the subclass decide which class to instantiate.
   * Also known as virtual constructor.
   * ##### Advantages
      * Allows the subclass to choose the type of object to create.
      * This promotes loose-coupling, i.e., objects are independent.
      * It eliminates the direct binding of application-specific classes to the code.
      * To achieve that, we use either an interface or an abstract class so that we can work with any class that is implementing this interface or abstract class.
      * We use this when a class doesn't know which subclass to instantiate.

2. #### Abstract Factory



3. #### Builder



4. #### Object Pool



5. #### Prototype



6. #### Singleton


7. #### Adapter

















26. #### Visitor
