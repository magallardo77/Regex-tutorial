# Regex Tutorial 

This file is a Regex tutorial targeted for users who plan on learing Regex expressions. Regex expressions are special character lines of code used for validation. 

## Summary
Phone Number Validation Using Regex Code: /^\d{3}-?\d{3}-?\d{4}-?$/

The tutorial will breakdown the following line of Regex and code and help those interested in becoming more proficient with Regex


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors are the first and last characters used to mark the begining and end of a Regex line of code. The begin character us `^` and the end character is `$`. Example: /`^`\d{3}-?\d{3}-?\d{4}-?`$`/
### Quantifiers
Quantifers can be used to determine gow many characters are expected, as well as, to optionally include a character. `{3}` expects three characters and `-?` states that the `-` is optional. Example: /^\d`{3}-?`\d{3}-?\d`{4}-?`$/
### Grouping Constructs
Grouping constructs capture substrings of an input string and can depict subexpressions out of the regex code. There is not a Grouping Constructs example in this code.
### Bracket Expressions
Similar to grouping constructs bracket expressions `[]` group a set of code together. Brackets were not used in this Regex Example. 
### Character Classes
Character classes are used to specify the characters you ecpect to see in your code. The most common are `[a-z]` & `[0-9]`. Character Classes were not used in this Regex Example.
### The OR Operator
The OR operator is characterized by the `|` character and is used to match expressions on the left and right of the character. The OR Operator was not used in this Regex Example.
### Flags
A Flag is a parameter used in the Regex code to filter search results. In this case a `d` flag was assigned and the code would listen for digit in the regex code. Example: /^\d{3}-?\ `d` {3}-?\d{4}-?$/
### Character Escapes
 Character Escapes are used to seperate sections of code. The `\` character is used in character escapes. Example: /^`\`d{3}-?`\`d{3}-?`\`d{4}-?$/
## Author

Miguel Gallardo

Github: magallardo77

Email: magallardo11@outlook.com
