## CASE Conditionals
A case function follows a WHEN THEN ELSE flow and returns a value.
## Example
<img width="272" alt="image" src="https://github.com/Eli-J-Paris/Today-I-Learned/assets/130601227/8cc2214d-31e4-47a7-b7c7-ff90e6a3973d">

In this example the CASE is part of the SELECT statment.

To start a case function first you need to start it off with the CASE keyword and to end the cae function you need to add the END keyword to bottom of the function.

Inside the case function is where you can add the WHEN keyword followed by conditionals. Then you need to add the THEN keyword. What comes after the THEN keyword is the value that is being returned if the the condtion(s) in the WHEN are met.

## WHEN 'ELSE'
If you need to evaluate mutiple conditions simply add more WHENs to the Case function. WHEN statemets functionaly act as if else statments seen in other languages returning the first value when a condition is evaluated to be be true and skipping over the rest.
## IF ELSE vs CASE
PostgreSQL does support IF ELSE statments which should be used to control the flow of a query. CASE statments are a function that return a value.
 


