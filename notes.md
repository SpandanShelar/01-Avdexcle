

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


.....................
DAY 3 
.....................
CONSDITIONAL FORMATING 
a tool that automatically changes the appearance of a cell or a range of cells—such as color, font, or fill—based on the specific values or conditions you set

Core Types of Rules
• Highlight Rules: Changes formatting if a cell is greater than, less than, or equal to a specific number, or if it contains a certain text or date string.
• Top/Bottom Rules: Targets statistical limits, such as the top 10% of values or cells performing below the group average.
• Visual Gauges: Applies a gradient of colors or visual meters directly inside the cells to show relative scale:

SORTING 
an Excel feature that rearranges your data into a specific order—such as alphabetical, numerical, or chronological—to help you organize and make sense of your spreadsheets.

Core Types of Sorting
• Alphabetical (Text): Arranges words from A to Z or Z to A.
• Numerical (Numbers): Sorts values from Smallest to Largest (ascending) or Largest to Smallest (descending).
• Chronological (Dates & Times): Arranges events from Oldest to Newest or Newest to Oldest.
• Custom Lists: Sorts by non-standard sequences like days of the week (Monday, Tuesday...) or t-shirt sizes (S, M, L, XL).
• Visual Sorting: Groups cells together by their cell fill color, font color, or conditional formatting icons.

Formula 
=SORT(array, [sort_index], [sort_order], [by_col])
• array (Required): The group of cells or the entire dataset you want to sort. (Tip: Do not include your headers in this range, or they will be sorted along with the data rows).
• [sort_index] (Optional): The column number you want to sort by, counting from the left side of your array. Defaults to 1 (the first column).
• [sort_order] (Optional): Use 1 for Ascending (A to Z, smallest to largest) or -1 for Descending (Z to A, largest to smallest). Defaults to 1.
• [by_col] (Optional): Use FALSE to sort by rows (downwards) or TRUE to sort by columns (sideways). Defaults to FALSE