# Day27

<br>
<br>
<b>Ques 1. Given an infix expression in the form of string str. Convert this infix expression to postfix expression.</b>
<br>
<br>
Infix expression: The expression of the form a op b. When an operator is in-between every pair of operands.<br>
Postfix expression: The expression of the form a b op. When an operator is followed for every pair of operands.<br>
Note: The order of precedence is: ^ greater than * equals to / greater than + equals to -. Ignore the right associativity of ^. Input: str = "a+b*(c^d-e)^(f+g*h)-i"<br>
Output: abcd^e-fgh*+^*+i-<br>
Explanation:<br>
After converting the infix expression<br>
into postfix expression, the resultant<br>
expression will be abcd^e-fgh*+^*+i- . <br>
Note :- Take all the required value from user.<br>
