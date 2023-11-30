# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > let, var and const

02. What is the definition of a function?

    > a subprogram that will do something when called or invoked. It performs a particular task. 

03. What are the `SOLID` principles?

    > Coding standards that we all need to use to keep our code understandable and universal.

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit.splice[2, 1];

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > const you.friends.push[them]
    const them.friends.push[you]

06. Give an example of a JavaScript `Conditional`:

    > A conditional statement is one that will determine whether a piece of code will run or not. An if statement is an example of this. IF "something happens" THEN "this code will run" 

07. What is the main difference between `parameters` and `arguments`?

    > Parameters are used to define a function. Arguments are the values we pass through functions to get our result we want. 

08. Instead of writing everything to the console, what is a better way to debug your code?

    > small changes, run code often

09. What is the difference between a `primitive` value and a `reference` value?

    > A primitive value is a single value that never changes (numbers, strings, boolean, etc). Reference date types are changeable, and they reference things that are larger like objects and arrays.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for(let i = -100; i < 100; i++){
        console.log(i)

    }
