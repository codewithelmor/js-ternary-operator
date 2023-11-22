# Ternary Operator 

The **`ternary operator`** in JavaScript is a concise way to write an if-else statement. It is also known as the conditional operator. The syntax is as follows:

```javascript
condition ? expressionIfTrue : expressionIfFalse;
```

Here's a simple example:

```javascript
let age = 20;
let message = (age >= 18) ? 'You are an adult' : 'You are a minor';

console.log(message);
```

In this example, if **`age`** is greater than or equal to 18, the variable **`message`** will be assigned the string 'You are an adult', otherwise, it will be assigned the string 'You are a minor'.

The ternary operator is a shorthand way to express simple conditional statements. It can make your code more concise and readable in certain situations. However, it's important to use it judiciously, as overly complex ternary expressions can make your code harder to understand.
