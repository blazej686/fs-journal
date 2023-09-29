# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | Let Var and Const |

02. What is the definition of a function?

    > | a program designed to perform a task. They are classified as an object |

03. What are the `SOLID` principles?

    > |
Single-responsibility Principle
Open-closed Principle
Liskov Substitution Principle
Interface Segregation Principle
Dependency Inversion Principle |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | by using array.delete[2].  |

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

    > |  let you = {
        name: "You",
        hair: true,
        friends: [1]
    }
    let them = {
        name: "Them",
        hair: false,
        friends: [0]
    }  |

06. Give an example of a JavaScript `Conditional`:

    > | if or an else  |

07. What is the main difference between `parameters` and `arguments`?

    > | Parameters are what is being used to check the augments. for example the parameter is y=10 the augment could be y = >20 |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | Using the debugging on the dev tools. |

09. What is the difference between a `primitive` value and a `reference` value?

    > | A primitive value is a number string boolean or symbol. if it is anything else it is a reference value.  |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | 
    
    for (
        let i = -100; i <= 100 ; i++) 
        print (i)
        |
