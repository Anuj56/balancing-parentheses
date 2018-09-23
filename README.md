# balancing-parentheses
A program that takes in a function as an input and returns whether or not the parentheses in the function are balanced.
It does this by using a stack. Whenever a '{', '[' or '(' character is seen, it pushes that character onto the stack.
When a '}', ']' or ')' character is met, it checks to see if the top of the stack has the matching opening paren.
If it does, it pops the top off and continues. If it does not, it outputs that the input function is unbalanced.
