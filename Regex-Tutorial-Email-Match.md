# Regex Tutorial for Matching an Email

## Summary

This tutorial explains how to use a regular expression (a.k.a. regex) to match emails. This is helpful for when you need to validate whether an email matches. The regex code being explained is: 
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors

The ^ symbol designates the beginning of the the string, while the $ symbol shows where the string ends.

### Quantifiers

The {2,6} in the expression is a quantifier. It indicates that the string should be between should be between 2 and 6 characters long. The other quantifier in the expression is the "+" symbol. It works to connect the the username, email service and domain name of the email together. 

### Character Classes

The \d in the second grouping is a character class and matches a single character that is a digit.

### Grouping and Capturing

The parentheses () separate the expression into smaller groups. 
    ([a-z0-9_\.-]+) matches the username 
    ([\da-z\.-]+) matches the email server
    ([a-z\.]{2,6}) will match the domain name of the email (for example, .com or .edu)

### Bracket Expressions

The [] symbols in this expression group items and indicate what will be allowed to appear in that specific section. Here is an explanation of the first bracket section in the expression: [a-z0-9_\.-] matches any character a-z, 0-9 and matches "_", ".", and "-". The second bracket section, [\da-z\.-] matches any character a-z, ".", and "-". The third bracket, [a-z\.] matches any character a-z and ".".

### Greedy and Lazy Match

The "+" symbol is a greedy operator. It expands the match as far as it can.

## Author

Andrea Rowland
https://github.com/Andrea-Rowland
