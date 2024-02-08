# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > A namespace is something you place at the top of your files so that every file can see what is  inside. 

02. What is the difference between a `class` and an `interface`?

  > A class is something you put inside of a file to describe the object within it. An interface is a file that contains a set of behaviors that will be available when you want to use them in your files to help modify your classes.

03. What is the method that returns an instance of a class, yet it has no return type?

  > VOID 

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > An access modifier is what tells your project what and when a method will be available. This modifier is public- stating that all the files can see this method. 

06. In the Car example what is `string` an indication of?

  > String is the data type of that Data. It is a "string".

07. In the Car example what is `abstract` preventing?

  > Abstract is preventing this method to be used on its own. It needs to  have more information from the class in order to be understood. 

08. In a SQL table, what is the difference between information in a row and information in a column?

  > Info in a column are the categories to the table whereas info in a row is another row of the same info but just another set of data for that table.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE characters (
    id INT AUTO-INCREMENT PRIMARY KEY, 
    name STRING(20) NOT NULL, 
    age STRING(3) NOT NULL, 
    description STRING(500) NOT NULL,

  )


10. In SQL how can you query more than a single table? Provide an example.

  > You use the JOIN method. 
  JOIN accounts ON characters.creatorId = account.id 
