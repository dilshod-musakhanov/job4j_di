## About the project "job4j_di"

A project for learning the concept of "Dependency Injection" (DI) 

The idea of DI is as follows:

- There is an object container, in which we will register the classes whose objects we want to have in our project. 
- In our example, we will register Tracker, StartUI, and ConsoleInput there.
- The object container, within the scope of DI, is called the "Context", which holds objects related to the domain of our project.
- After registering the classes, the Context starts initializing the objects. 
- It builds a dependency tree by first creating objects without dependencies and then creating objects with dependencies.
- After initialization, the programmer can obtain the required object from the Context.

---
Author: Dilshod Musakhanov
Date: 07/03/2023
Contact: musakhanov@yahoo.com
