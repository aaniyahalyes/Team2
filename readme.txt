Team Members: Evan Abrahamson, Aaniyah Alyes, Isabelle del Castillo

Evan Abrahamson:

Estimated Time to Produce Solution: 15 hours/2 Days on and off

Shortcomings/Concerns with the Solution: N/A

Aaniyah Alyes:

Estimated Time to Produce Solution: 20 hours/3-4 Days on and off

Shortcomings/Concerns with the Solution: Shortcomings/Concerns that I’ve come across was redirecting the input file from the command prompt.

Isabelle del Castillo:
Estimated Time to Produce Solution: 2 Days on and off

Shortcomings/Concerns with the Solution: Shortcomings/Concerns that I’ve come across was redirecting the input file from the command prompt.


The reason for this is because in the actual file/original code there is a definition '#define my_bytes int' which means 'my_bytes' is an alias for the data type 'int'. During the preprocessing process, the preprocessor encounters 'my_bytes' and replaces it with 'int' which results in 'byte n'.

The reason for this is because in the original code, #if and #endif are used a conditional statements to include or exclude code blocks that are determined by what the 'PRINT' value is. The preprocessor looks through the value of 'PRINT' to see if the value matches the condition, and if it doesn't then it is excluded.

in the preprocessed output is shown as 'int flipped = (-10);'
// whereas in the actual file, its written as 'int flipped = MY_FLIP(MY_N);'
// These difference occur because

The reason for this is because MY_FLIP is defined as #define MY_FLIP(n) (-n) in the original code and when it is encountered, the preprocessor expands it by replacing MY_N with its defined value of 10. 




the new output is different because the old output contained errors when	
// attempting to compile. In the original code,	the 'printf' statement that was	inside 
// the conditional code blocks was incorrect. In the new code, to fix the error, the    
// 'printf' contained 'flipped' which was changed to to correctly display the value     
// 'mult2'. The reason 'flipped' was removed was because it was an undefined variable which was 
// not defined anywhere else in the code. 