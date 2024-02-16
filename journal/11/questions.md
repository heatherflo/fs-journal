# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > Inheritance helps us make models (classes) that are 'children' within each other so we can call upon some values while hiding others- such as in account and profile. We can call a profile and show items here but also call on account without having to show all the items here. 

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > When you inherit class properties you don't have to inherit the whole class but you don't have to access the whole thing - keeping some values hidden.

3. How does ***accessibility*** affect inheritance?

  > Accessibility is the ability to make a class public (seen by all the files) or internal (private within the one file)

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > A primary key is a unique value within a table. A foreign key is a value will reference another table. 

5. What is an ***alias***?

  > An alias is another way to name a table elements (columns) so that you can identify them easier (when the columns have similar names).

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```
  > SELECT 
    doctors.*,
    patients.*
    FROM doctors
    JOIN patients ON doctors.patientId = patient.id 
    WHERE doctors.id = LAST_INSERT_ID();
    
