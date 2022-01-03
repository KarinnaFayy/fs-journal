# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
-Abstraction
-Encapsulation
-Inheritance
-Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is a process of binding the data with the functions which act upon the data. Encapsulation allows us to control and validate the data. 

```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The Single Responsibility Principle.

```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is a blueprint which you use to create objects. An object is an instance of a class - it's a concrete 'thing' that you made using a specific class. So, 'object' and 'instance' are the same thing, but the word 'instance' indicates the relationship of an object to its class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Proxy is a structural design pattern that provides an object that acts as a substitute for a real service object used by a client. A proxy receives client requests, does some work (access control, caching, etc.) and then passes the request to a service object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
Model–view–controller (MVC) is a design pattern commonly used for developing user interfaces that divide the related program logic into three interconnected elements. This is done to separate internal representations of information from the ways information is presented to and accepted from the user.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The Controller is responsible for controlling the application logic and acts as the coordinator between the View and the Model. The Controller receives an input from the users via the View, then processes the user's data with the help of Model and passes the results back to the View.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
A service layer is an additional layer in an MVC application that mediates communication between a controller and repository layer.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model is responsible for managing the data of the application. It receives user input from the controller. The view renders presentation of the model in a particular format. The controller responds to the user input and performs interactions on the data model objects.
```
