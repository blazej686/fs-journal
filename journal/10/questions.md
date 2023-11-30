# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | It is kind of like the export class in JS that allows it to be accessed in other files of the app.|

02. What is the difference between a `class` and an `interface`?

  > | A class isn't abstracted and an interface is completely abstracted  |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | Void |

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

  > | Public |

06. In the Car example what is `string` an indication of?

  > | A return time |

07. In the Car example what is `abstract` preventing?

  > | It is preventing the car from being instantiated  |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | Columns house the data "title" such as name id. Rows house the data of each item that is in the table such as the id number and name of object. |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > | CREATE TABLE IF NOT EXISTS characters(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(255) NOT NULL,
    age VARCHAR(255) NOT NULL,
    description VARCHAR(255) NOT NULL,
  ) DEFAULT CHARSET utf8 COMMENT'';
  |

10. In SQL how can you query more than a single table? Provide an example.

  > | SELECT
rec.*,
acc.*
FROM characters char
JOIN accounts acc ON char.creatorId = acc.id
WHERE char.id = LAST_INSERT_ID();"; |
