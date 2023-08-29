# Regular Expressions (Regex)
A Regular Expression is combination of characters that is used to search through a string of text.
It accepts certain set of strings and reject the rest.

## Summary
I would like to briefly dive deeper into the patterns applied for email pattern search. The regex for email
pattern is: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
What are anchors? Anchors are special characters in a regular expression that doesn't match any other characters. 
In our example, the anchors are ^ and $. It indicates where the start and end of the a line or a string. 

### Quantifiers
What are quantifiers? It defines how many times an element can appear in the input to match the character. 
In our example, the + and {2,6} are the components of quantifiers. 
* +: Matches one or more
* {2,6}: 2-6 characters min/max

### Grouping Constructs
What is Grouping Contructs? It gives you the ability to group characters together, mostly covered in brackets expression.

### Bracket Expressions
What is Bracket Expression? Gives you a list of characters that are enclosed in a bracket. It is use to match single characters in a list. 

### Character Classes
What is Character Classes? Its a set of characters enclosed in a square bracket. It specifies that the character that will be successfully match a string character from the input string.

### The OR Operator
What is the OR operator? It is used to match one or multiple patters or such as this OR that.

### Flags
Flags are optional parameter to a regex for a specific behavior 

### Character Escapes
It allows you to match character that would have a special meaning in regex. You must use an escape code to match the characters. 

## Author
Joseph Malonzo 
Github - Joseph388754

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
