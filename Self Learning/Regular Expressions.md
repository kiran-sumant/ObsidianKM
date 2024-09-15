|     |                                                         |       |                    |
| --- | ------------------------------------------------------- | ----- | ------------------ |
| ^   | Start of string, or start of line in multi-line pattern | \c    | Control character  |
| \A  | Start of string                                         | \s    | White space        |
| $   | End of string, or end of line in multi-line pattern     | \S    | Not white space    |
| \Z  | End of string                                           | \d    | Digit              |
| \b  | Word boundary                                           | \D    | Not digit          |
| \B  | Not word boundary                                       | \w    | Word               |
| \<  | Start of word                                           | \W    | Not word           |
| \>  | End of word                                             | \x    | Hexade­cimal digit |
| *   | 0 or more                                               | \O    | Octal digit        |
| +   | 1 or more                                               | {3,}  | 3 or more          |
| ?   | 0 or 1                                                  | {3,5} | 3, 4 or 5          |


Ranges are inclusive.
Add a **"?"** to a quantifier to make it ungreedy.