# A NEAR-calculator that obeys BODMAS

This code is used to take an input of an expression as a string. It will then traverse through the whole string to solve the mathematical equation. Using the Infix-Potsfix Solution technique.

The code will basically solve the basic arithmetic problems including:
- Addition
- Subtraction
- Multiplication
- Division
- Power

It will solve this obeying the BODMAS rules.

It does the above by first converting the infix string expression e.g. `1+2` to postfix expression e.g. `1 2+`. Even the largest of expressions can be converted to a postfix expression and hence this will allow us to solve the expression using upholding the precedence law.

We will be using stacks to help us solve this particular type of expression.
