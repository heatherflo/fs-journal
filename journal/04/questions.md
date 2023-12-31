# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > Asynchronous code runs in the background of a webpage without having to reload the webpage- therefore making things faster and easier to load. It allows you to fun multiple lines of code at once without making sure one is done first before starting another. 

  >Synchronous code is code that only lets one line of code run at a time. It has to be completed before another line of code can start. 

02. What is an event listener?

  > An event listener is a function that is run specifically when you want to 'wait' for something to happen so it can respond when it's ready. It listens for the callback functions orders and tell it when its ready. 

03. What does *REST* stand for, and in simple terms what does it mean??

  > REST stands for Representational State Transfer and it essentially is the rules on how api's should work and transfer information.  

04. What is a callback / higher order function?

  > A callback is a function that executes when it knows something has happened. The listener tells it something has happened and then it can run. A higher order function is when you put in one or more functions in as arguments.  

05. What is a `promise`? How do you capture an error from a `promise`?

  > A promise is a function that will run and give you two possible outcomes. 1: that the function may run and be completed (get a response) or 2. that the function may run and be rejected. To capture an error from a promise you can 'catch' it using the try/catch method. 

06. Name three processes used to make requests over `HTTP`?
                                                     
  > POST, GET, PUT

07. What does the `API` acronym stand for?

  > Application Programming Interface

08. What must you do in order to `await` a promise inside of a function?
                                                                                                        
  > The promise must be an async function to start. Then tacking on 'await' will give the function the ability to wait for another function/order to be completed before coming back with a response (or not). 

09. What is the purpose of encapsulation in programming?

  > Its so we can hide important information in a class so they can't be accessed as easily to change. 

10. What is `HTTP` response code for a successful request?

  > We want to see a 200 OK to show that the response from a get was successful .

11. What is a 400 error?

  > A bad request: something went wrong in the request to get data from the API. 
