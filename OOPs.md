- Things an objects knows about itself(object state) are called **instance variables**
- Things an object can do are called **methods**
- **Class** is a blueprint for an **object**

- For creating and using an object, you need two classes. 

- Each time an object is created in Java, it goes into an area of memory known as The Heap. 
- A class can inherit instance variables and methods from a more abstract superclass. 

- Objects can't be stored inside variable ( that's not happening actually), they live only in garbage-collection heap.

**Object reference variable**
Dog myDog = new Dog();

myDog is a object reference variable
- All references for given JVM will be same size regardless of object they reference.
- No arithmetic in reference variable. 

Once the object referenced by the reference variable changes,and no other variables reference that object, it is eligible for Garbage Collection.

*Array is an object, even though it's an array of primitives.*
