# Checking-if-braces-brackets-or-square-brackets-are-balanced

This is an implementation of one of the applications of the stack which is: 
    
    -> To check if an arithemetic operation has balanced parenthesis
    
    The algorithm:
    
    ---> Declare a character stack S.
    ---> Now traverse the expression string exp (the array of braces,brackets).
    ---> If the current character is a starting bracket (‘(‘ or ‘{‘ or ‘[‘) then push it to stack.
    ---> If the current character is a closing bracket (‘)’ or ‘}’ or ‘]’) then pop from stack and if the popped character is the matching          starting bracket then fine else parenthesis are not balanced.
    ---> After complete traversal, if there is some starting bracket left in stack then “not balanced”
