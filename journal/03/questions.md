# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > Abstraction, Encapsulation, Inheritance, Polymorphism 

02. How does `export` differ from `export default`?
  
  > When you export, you can export values one at a time or all in one statement. You then have to recall these each by their name when importing them later.  Exporting these items as default they will allow you to import them as the same value later no matter what (as default values) without calling them out by name.  

03. What is Encapsulation?
  
  > Encapsulation combines code into a single unit keeping it organized and helps prevent accidental changes or modifications. 

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > Proxy objects allow us to create an object that can be used in place of original objects. This allows is to redefine the original objects properties. It essentially is a larger box around the object we are 'targeting'.

05. What the difference between a `class` and an instance of a `class`?
  
  > A class is an object you create- a blueprint that holds and encloses all your objects (instances of that class you created.) you can then recall these instances elsewhere using the this.__ functionality. In the 'instance' of this value within the class- you can recall it. 

06. What is a computed Property?
  
  > A computed property is a value of an expression inside an object. It is something that has a value to it and it is inside the object itself. It can be an array or an expression. We can use them as properties. 

07. What is the purpose of the `MVC` pattern?
  
  > To structure the code in a way to keep it more organized. This will help when we have very large programs that we are trying to put together. 

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > The controllers job is to house all the 'controls' or functionality of the items. You don't change any data here. You just do something with it. This also takes in actions from users. 

09. What is the job of the `Service` in `MVC`?
  
  > This is the place where we change all the data (make modifications to it.)

10. What is the job of the `Model` in `MVC`?
  
  > This is the blueprint of what the data will look like in the appstate. 
