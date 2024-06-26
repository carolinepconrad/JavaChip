
![JAVACHIP GIF](images/JAVACHIP.gif)

###### Created by: Nick Benson, Kaleb Powell, Caroline Conrad
---
# JavaChip ☕️
### ☕️ Overview:
JavaChip is a domain-specific programming language designed for coffee enthusiasts and baristas alike. It offers a unique syntax inspired by the world of coffee, allowing users to express themselves in a language that resonates with their passion for java. With features tailored to the coffee experience, JavaChip aims to provide a fun and intuitive way to write code while enjoying a cup of your favorite brew.

### ☕️  Instructions:
__1. Download & Set Up__
- Download the JavaChip code from the repository
- Ensure you have Visual Studio Code installed
-  If not previously done, [install and set up Node.js](https://nodejs.org/en/download) to execute the code
  
__2. Running the Demo__
- Open your terminal through Visual Studio Code
- Type in the following command in the terminal:
```bash
node.js interpret.js demo.chip
```
### ☕️  Demo Code
```JavaChip
$ This is our demo code!
-10 sprinkles 1
5 frappe 5
50 ice 10
100 caffeine -20
10 sips 555
*hi* sips *here*
withLegs *hello*
$$$ 
This is a multiline comment
$$$
```
### ☕️ Syntax Rules and Variable Types:

| Syntax                | Description                                                                   |
|-----------------------|-------------------------------------------------------------------------------|
| Single Line Comments  | Use `$` to add comments to your code.                                         |
| Multi-Line Comments   | Enclose multi-line comments between `$$$`.                                    |
| Assignment Operator   | Use `~` for variable assignment.                                              |
| Operators             | - Multiplication: `caffeine`                                                  |
|                       | - Division: `frappe`                                                          |
|                       | - Addition: `sprinkles`                                                       |
|                       | - Subtraction: `ice`                                                          |
| Commands              | - `order`: Prints everything following this command to the console.           |                                                
|                       | - `withLegs`: adds ({) to the end of a string                                 |
| Variable Types        | - Integer: `oz`                                                               |
|                       | - String: `roast` (strings are enclosed in `*`)                               |
|                       | - Boolean: `isDecaf`                                                          |


### ☕️ Grammar:
```
<program> ::= <statement_list>

<statement_list> ::= <statement> | <statement> <statement_list>

<statement> ::= <assignment_statement> | <order_statement> | <comment_statement> | <with_legs_statement>

<assignment_statement> ::= <identifier> <assignment_operator> <expression>

<order_statement> ::= "order" <string_value>

<comment_statement> ::= "$" <comment_text> | "$$$" <multi_line_comment_text> "$$$"

<with_legs_statement> ::= "withLegs" <string_value>

<expression> ::= <term> | <expression> <add_operator> <term>

<term> ::= <factor> | <term> <subtract_operator> <factor>

<factor> ::= <number> | <identifier> | <string_value> | "(" <expression> ")" | <factor> <multiply_operator> <factor> | <factor> <divide_operator> <factor>

<add_operator> ::= "sprinkles"

<subtract_operator> ::= "ice"

<multiply_operator> ::= "caffeine"

<divide_operator> ::= "frappe"

```
### ☕️ State of the Language:
As of right now, the only **working** pieces of our language are:

- Tokenizing all the code
- Simple arithmetic operations
- `withLegs` command
- `sips` (joining two numbers together)
- Single and multiline comments

Things that are **not working** include:

- Variable assignment
- Concatenation between strings
- Booleans


---
###### langcraftSP24 -- Programming Languages; CIS 333; SP 2024
