# Regular Expression Hub

# Tools
* [Reg Exr](https://regexr.com/)    
* [Regex 101](https://regex101.com/)      
* [Regex Pal](https://www.regexpal.com/)    

# References  
* [Learn Regular Expressions (Regex) - Crash Course for Beginners - YouTube](https://www.youtube.com/watch?v=ZfQFUJhPqMM)  

# Cheat Sheet Reference 
* [QuickRef.ME](https://quickref.me/regex)

# Cheat Sheet      
## Modifiers
* d Flag - Expression match should contain the start and end string
* g Flag - Expression should be tested against all possible matches in a string
* i Flag - Do a case-insensitive search
* m Flag - Multi-line search
* s Flag - Allows . to match newline characters
* u Flag - Treat a pattern as a sequence of unicode code points
* y Flag  - Perform a "sticky" search that matches starting at the current position in the target string

## Groups and Ranges

* OR Group - (x|y) Matches either "x" or "y"
* Specify Range - [abcd] is the same as [a-d]. They match the "b" in "brisket", and the "c" in "chop".
* Negated Range - [^a-c] They initially match "on" in "bacon" and "hop" in "chop" with global flag set
* Capturing Group - Matches x and remembers the match. (go)+ means go, gogo, gogogo and so on
* Capturing Group \nth - Where "n" is a positive integer. \1 refers to the first capturing group in the regular expression. \2 will refer to the second capturing group and \n will refer to an nth capturing group   

