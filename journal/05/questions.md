# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > Create, Read, Update, Delete 
  Persistent storage (even after powering down) that isn't stored somewhere else on volatile storage.

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > CREATE: POST used to create resources
    READ: GET used to retrieve a resource 
    UPDATE: PUT used to create or update a resource 
    DELETE: DELETE uses to delete a resource 

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > Object Relational Mapping | We use Mongoose when interacting with MongoDB.

04. Which two `HTTP` request types include a body?

  > When we use POST and PUT we include a body because those are user updated changed and information being sent to to the server. 

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | ANSWER HERE |

06. What are the three types of data relationships? Provide an example of each.

  > 1:1 A one to one relationship between one thing and another thing. Each side is a single thing. One author writes a book(one book was written by one author)
  >1:N A one to many relationship between one thing and many things. One side can only be a single thing and other can be many things. One blog post has many comments(many comments on one blog post).
  >N:M a many to many relationship where both sides things MAY relate to each other in many ways. One author may have written many books or multiple authors may have written one book. It could go either way. 

07. What is middleware?

  > Middleware is a software that is run behind the scenes to connect applications, users and databases. 

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | ANSWER HERE |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | ANSWER HERE |

10. What is a ***virtual property***?

  > | ANSWER HERE |
