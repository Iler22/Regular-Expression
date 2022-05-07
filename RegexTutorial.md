# Regular Expression Tutorial

This gist is a tutorial on how to use regular expressions also known as (Regex).

## Summary

Regular expressions are patterns used to match character combinations in strings. For the purpose of this tutorial we will be focusing on email validation.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)

## Regex Components

### Anchors

Anchors are used to match the position before, after or between characters and can be used in regex to match a certain position for email validation. When applying the caret '^' it matches the position before the first character of a string. Therefore if the caret was placed at the beginning of xyz then those characters would be matched. However if the caret is placed at y then the characters would not be matched.

### Quantifiers

The {min, max} quantifier can be used in email validation to limit the amount of characters that a user can enter to generate a email. If on the minimum value is provided like {2, } then a user will be able to have a infinite amount of characters. Therefore it is better to limit a user to a certain amount of characters for example {1, 8}.

### Grouping Constructs

A regular expression can be grouped together using round brackets or parentheses. The purpose of this is to allow a quantifier to apply to that specific group for email validation or to restrict alteration from that specific character set. Curly brackets are used by a quantifier to create specific limits as explained above and square brackets are used to define a character class.

### Bracket Expressions

A character class also known as a character set, can be used to tell a regex engine to match only one out of several character inputs available. In order to do this a developer would input the possible characters between square brackets. This could be done using case sensitive or numeric values like: [a-z], [0-9], or [A-Z].

## Author

This Regex tutorial was made by Iler Watson. Please contact me at [ilerwatson22@gmail.com](mailto:ilerwatson22@gmail.com). View more of my work in GitHub at https://github.com/Iler22
