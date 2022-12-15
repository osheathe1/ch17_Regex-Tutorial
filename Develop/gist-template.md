# Tutorial: Regex matching Hex Value

What is Regex Matching? A regular expression (aka Rational Expression)?

## Summary

Regular expressions sometimes referred to as rational expressions is a sequence of characters that specifies a search pattern in text. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation. 

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
/.../ all regex notation must be wrapped in slashes.

### Anchors
The anchors used to contain this regular expression are: ^ to start, and $ to finish.

### Quantifiers
In this example, we used + to communicate there is another sequence to be matched as a greedy quantifier. We also used {2,6} as another greedy quantifer to specify the input should be a minimum of 2 characrtors to a maximum of 6 characters.

### Grouping Constructs
Grouping constructs allows the ability to check multiple parts of a string. (...):(...) each expression is nested within parentheses

### Bracket Expressions
Bracket expressions are a list of characters and/or character classes enclosed in brackets [].

[...] Square brackets will return any items that match

{...} Curly brackets return the exact
Curly braces are used to specify an exact amount of things to match.

(...)
### Character Classes
In this regular expression, the charactor class /d is used which in Javasctipt classifies the use of any digit from 0 to 9.

### The OR Operator
| OR operator will return an item if any condition is met.

### Flags
Flags are placed at the end of a regex statement. g Global search

i Case sensitive

m Multi line search

### Character Escapes
\ Placed before character to escape base functionality defined withing regex.

## Author

JaMionn Fletcher = Student learning software development.
