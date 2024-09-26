| Operator | Function                                                |
| -------- | ------------------------------------------------------- |
| ^        | Start of string, or start of line in multi-line pattern |
| \A       | Start of string                                         |
| $        | End of string, or end of line in multi-line pattern     |
| \Z       | End of string                                           |
| \b       | Word boundary                                           |
| \B       | Not word boundary                                       |
| \<       | Start of word                                           |
| \>       | End of word                                             |
| *        | 0 or more                                               |
| +        | 1 or more                                               |
| ?        | 0 or 1                                                  |

| Operator | Function           |
| -------- | ------------------ |
| \c       | Control character  |
| \s       | White space        |
| \S       | Not white space    |
| \d       | Digit              |
| \D       | Not digit          |
| \w       | Word               |
| \W       | Not word           |
| \x       | Hexade­cimal digit |
| \O       | Octal digit        |
| {3,}     | 3 or more          |
| {3,5}    | 3, 4 or 5          |

| Operator | Function                           |
| -------- | ---------------------------------- |
| .        | Any character except new line (\n) |
| (a\|b)   | a or b                             |
| (...)    | Group                              |
| (?:...)  | Passive (non-c­apt­uring) group    |
| [abc]    | Range (a or b or c)                |
| [^abc]   | Not (a or b or c)                  |
| [a-q]    | Lower case letter from a to q      |
| [A-Q]    | Upper case letter from A to Q      |
| [0-7]    | Digit from 0 to 7                  |
| \x       | Group/­sub­pattern number "­x"     |

Ranges are inclusive.
Add a **"?"** to a quantifier to make it ungreedy.