# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | It allows you to pass down elements to another file in your workspace |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | yes a class gets all members of that class that is passed to it via extending it. |

3. How does ***accessibility*** affect inheritance?

  > | Private members are not visible from the child class and public ones are visible and can be accessed as well. |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | Primary key is a sql table item that is assigned to the item and the foreign is what it looks for when doing a "virtual"  |

5. What is an ***alias***?

  > | It is a way to rename things in SQL to a shorthand so you don'thave to type it all out each time. |

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

  > | ANSWER HERE |
