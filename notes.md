

For giving the random values in sum 
We have used [Randbetween] FOR adding the random values 
Then the values start fluctuating so we need to 
Control + D and R

Co-py the whole data then paste it in selected Range 
Random values assigned 

For making the total we use 
=SUM{--,--,--}
ALSO , {Alt + =}
 command + shift + T 


Formula for 
Average-- =Average{--}
Maximum-- =Maximum{--}
Minimun-- =Min{--} 

This are the aggregates functions avg,max,min 


how to get percentage 
=E17/300*100 


if , if AND  ,IF OR 
=IF(I17>=35,"pass","fail")
=If AND is used situation when there is and compulsion of any 2 things 
=If OR is used in situation where there is and optional requirement ,... which termed as Or 



.....................
DAY 2 
.....................
NESTED IF AND  IFS FUNCTIONS

IF Function in Excel performs a logical comparison and returns one value if a condition is true and another value if it is false.

Syntax
The basic structure of the formula is:
=IF(logical_test, value_if_true, value_if_false)
• logical_test: The condition you want to check (e.g., A1>50, B2="Yes").
• value_if_true: What Excel should show if the condition is met. Text needs quotation marks like "Pass".
• value_if_false: What Excel should show if the condition is not met.

NESTED IF 
If function inside another to test multiple conditions and return different outcomes.
=IF(condition1, result1, IF(condition2, result2, IF(condition3, result3, result4)))

IFS 
The IFS Function in Excel checks multiple conditions in order and returns a value for the first condition that evaluates to TRUE.
• =IFS(logical_test1, value_if_true1, [logical_test2, value_if_true2], ...)
• You can test up to 127 different conditions in a single formula.