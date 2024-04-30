
![JAVACHIP GIF](images/JAVACHIP.gif)

###### Created by: Nick Benson, Kaleb Powell, Caroline Conrad
---


# JavaChip ☕️
### Overview:
JavaChip is a domain-specific programming language designed for coffee enthusiasts and baristas alike. It offers a unique syntax inspired by the world of coffee, allowing users to express themselves in a language that resonates with their passion for java. With features tailored to the coffee experience, JavaChip aims to provide a fun and intuitive way to write code while enjoying a cup of your favorite brew.

### Instructions:
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
### Demo Code
```JavaChip
$$$ This is the sample demo code for JavaChip

order *Welcome to the JavaChip Coffee Shop!*

oz ~ 12
roast ~ *dark* 
isDecaf ~ false  

order *Your coffee order:*
order *Size:* sprinkles oz sprinkles *ounces*
order *Roast:* sprinkles roast
order *Decaf:* sprinkles isDecaf


caffeineContent ~ oz * 5  
order *Caffeine Content:* sprinkles caffeineContent sprinkles *mg*


sugar ~ 2  
finalOz ~ oz sprinkles sugar  
order *Final Size with Sugar:* sprinkle finalOz sprinkle *ounces*


order withLegs *Your coffee is ready! Enjoy!*


```

### Features:
- Syntax Rules: JavaChip's syntax rules are designed to resemble common coffee-related terms and actions. From single line comments to blocks of code represented by coffee mugs, JavaChip offers a refreshing take on traditional programming syntax.
- Variable Types: JavaChip supports integer, string, and boolean variable types, allowing users to manipulate data in their programs with ease.
- Keywords: Keywords such as "order" and "dirty" add flavor to JavaChip's lexicon, enabling users to express themselves in a language that speaks to their love for coffee.
- Built-in Functions: JavaChip comes with built-in functions tailored to coffee-related tasks, making it easy to perform common operations such as calculating caffeine content or customizing your drink order.

### Syntax Rules and Variable Types:

| Syntax                | Description                                                                   |
|-----------------------|-------------------------------------------------------------------------------|
| Single Line Comments  | Use `$` to add comments to your code.                                         |
| Multi-Line Comments   | Enclose multi-line comments between `$$$`.                                    |
| Single Commands       | End each command with `({)`.                                                  |
| Blocks of Code        | Begin and end blocks of code with `\_/`.                                        |
| Assignment Operator   | Use `~` for variable assignment.                                               |
| Operators             | - Multiplication: `caffeine`                                                   |
|                       | - Division: `frappe`                                                           |
|                       | - Addition: `sprinkles`                                                        |
|                       | - Subtraction: `ice`                                                           |
| Commands              | - `order`: Prints everything following this command to the console.           |                                                |
|                       | - `withLegs`: Wraps a string with a to-go-cup symbol for printing to the console. |
| Variable Types        | - Integer: `oz`                                                                |
|                       | - String: `roast` (strings are enclosed in `*`)                               |
|                       | - Boolean: `isDecaf` 


### Keywords:
- order: prints everything following this command to the console
- dirty: doubles the number
- withLegs: wraps a string with a to go-cup symbol for printing to the console 

### Grammar:
JavaChip's grammar is designed to be intuitive and easy to understand, with syntax rules that mimic common coffee-related actions and terminology.
[NEED TO ADD 
___
 ☕️ Feel free to brew up some code with JavaChip! ☕️
___
### State of the Language:

---
###### langcraftSP24 -- Programming Languages; CIS 333; SP 2024
