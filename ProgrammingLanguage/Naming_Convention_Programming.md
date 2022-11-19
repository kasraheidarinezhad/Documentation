# Naming convention in programming
In computer programming, a naming convention is a set of rules for choosing the character sequence to be used for identifiers which denote variables, types, functions, and other entities in source code and documentation.

Reasons for using a naming convention (as opposed to allowing programmers to choose any character sequence) include the following:[[1]](https://en.wikipedia.org/wiki/Naming_convention_(programming))

To reduce the effort needed to read and understand source code;
To enable code reviews to focus on issues more important than syntax and naming standards.
To enable code quality review tools to focus their reporting mainly on significant issues other than syntax and style preferences.

Programmers employ numerous tactics to ensure readable and organized code. These include:

* Using naming conventions for variables;
* Placing whitespaces, indentations and tabs within code;
* Adding comments throughout to aid in interpretation.

Let’s take a look at some naming conventions.[[2]](https://curc.readthedocs.io/en/latest/programming/coding-best-practices.html)

Multiword Delimited
This convention is to separate words in a variable name without the use of whitespace. Whitespace within variables is usually difficult for programming languages to interpret. Because of this variables must be delimited in some way. Here are several delimiting conventions commonly used in code:

**Snakecase:** Words are delimited by an underscore.
```
variable_one
variable_two
```
**Pascalcase:** Words are delimited by capital letters.
```
VariableOne
VariableTwo
```
**Camelcase:** Words are delimited by capital letters, except the initial word.
```
variableOne
variableTwo
```
**Hungarian Notation:** This notation describes the variable type or purpose at the start of the variable name, followed by a descriptor that indicates the variable’s function. The Camelcase notation is used to delimit words.
```
arrDistrubuteGroup  //Array called “Distribute Group”
sUserName           //String called “User Name”
iRandomSeed         //Integer called “Random Seed”
```
These conventions are by no means binding, but instead examples of how many programmers format their code. Consistency and readability are key ideas that should be utilized in the naming of variables. Regardless of how you choose to name your variables, always ensure that your naming conventions are consistent throughout the code. Consistency allows others to more easily understand your code.

For more information, see "https://curc.readthedocs.io/en/latest/programming/coding-best-practices.html"